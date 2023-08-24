**Introduction to HTML: Lesson 5 - Responsive Web Design**

Welcome back to our HTML course! In this lesson, we'll delve into the concept of responsive web design, which is essential for creating web pages that look great on various devices, from desktops to smartphones.

**Understanding Responsive Web Design**
Responsive web design is an approach that ensures your web pages adapt and respond appropriately to different screen sizes and devices. With the growing variety of devices used to access the internet, it's crucial to create a seamless user experience across all platforms.

**Viewport Meta Tag**
The `viewport` meta tag helps control the layout on mobile browsers. It ensures that the webpage scales and adjusts its content to fit different screen sizes.

```html
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

**Fluid Grids and Flexible Images**
A key aspect of responsive design is using relative units like percentages for widths and flexible units like `em` or `rem` for font sizes. This allows elements to adapt fluidly.

```css
.container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
}

img {
    max-width: 100%;
    height: auto;
}
```

**Media Queries**
Media queries allow you to apply different styles based on the device's characteristics, such as screen width, orientation, and resolution.

```css
@media (max-width: 768px) {
    /* Styles for screens with width up to 768px */
}
```

**Responsive Navigation**
For navigation menus, consider using a collapsible menu (often called a "hamburger" menu) for smaller screens to save space.

```html
<nav class="navbar">
    <div class="menu-icon">
        <i class="fa fa-bars"></i>
    </div>
    <ul class="menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>
```

**Your Task: Building a Responsive Page**
For this lesson's assignment, enhance your `contact.html` page from the previous lessons to make it responsive. Apply the viewport meta tag, create a fluid grid layout, and use media queries to adjust styles for different screen sizes. You can also experiment with responsive navigation.

**Conclusion**
Great job! You've completed the fifth lesson of our HTML course. You now understand the importance of responsive web design and how to create web pages that adapt to various devices. By implementing responsive techniques, you're ensuring that your web content reaches and engages users on any screen size. In the next lesson, we'll introduce you to some advanced HTML features and concepts. Keep up the excellent work on your journey to becoming a skilled web developer!