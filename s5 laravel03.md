**Introduction to Laravel API Development: Lesson 3 - Creating Routes and Controllers**

Welcome to the third lesson of the "Introduction to Laravel API Development" course! In this lesson, we'll explore how to create routes and controllers in Laravel to handle incoming API requests and manage the logic of your API endpoints.

**Creating API Routes**
Laravel provides a dedicated file, `routes/api.php`, for defining API routes. Open this file and start defining the routes for your API endpoints.

```php
use Illuminate\Support\Facades\Route;
use App\Http\Controllers\ApiController;

Route::get('/items', [ApiController::class, 'getItems']);
Route::post('/items', [ApiController::class, 'createItem']);
Route::put('/items/{id}', [ApiController::class, 'updateItem']);
Route::delete('/items/{id}', [ApiController::class, 'deleteItem']);
```

**Creating Controllers**
Controllers are responsible for handling the logic of your API endpoints. You can generate a new controller using the `make:controller` Artisan command:

```
php artisan make:controller ApiController
```

Open the newly created `ApiController.php` file in the `app/Http/Controllers` directory. Define methods for each API endpoint:

```php
use Illuminate\Http\Request;
use App\Http\Controllers\Controller;
use App\Models\Item;

class ApiController extends Controller
{
    public function getItems()
    {
        $items = Item::all();
        return response()->json($items);
    }

    public function createItem(Request $request)
    {
        $item = Item::create($request->all());
        return response()->json($item, 201);
    }

    public function updateItem(Request $request, $id)
    {
        $item = Item::findOrFail($id);
        $item->update($request->all());
        return response()->json($item, 200);
    }

    public function deleteItem($id)
    {
        Item::findOrFail($id)->delete();
        return response()->json(['message' => 'Item deleted'], 200);
    }
}
```

**Testing Your API Endpoints**
Use tools like [Postman](https://www.postman.com/) or [curl](https://curl.se/) to test your API endpoints by sending HTTP requests to the routes you've defined.

**Your Task: Define Additional API Endpoints**
For this lesson's assignment, extend your API by defining additional endpoints, such as retrieving a single item by ID and implementing any other CRUD operations you might need.

**Conclusion**
Congratulations! You've completed the third lesson in the "Introduction to Laravel API Development" course. You've learned how to define API routes and create controllers to handle API logic in Laravel. Controllers play a central role in managing the business logic of your API endpoints. In the next lesson, we'll explore request and response handling in greater detail. Keep up the great work on your journey to mastering Laravel API development!