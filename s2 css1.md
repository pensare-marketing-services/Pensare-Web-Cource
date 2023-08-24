**Introduction to CSS: Lesson 1 - Cascading Style Sheets (CSS)**

Welcome to the CSS section of our course! By completing the HTML course, you've learned how to structure web content. Now, it's time to dive into the world of CSS, where you'll learn how to style and design your web pages to make them visually appealing and engaging.

**Understanding CSS**
Cascading Style Sheets (CSS) is a language used to control the presentation and layout of HTML elements. CSS allows you to define how elements should look, from their colors and fonts to their sizes and positions. With CSS, you can transform plain HTML documents into stunning and professional-looking web pages.

**Three Ways to Apply CSS**
1. **Inline Styles:** Apply styles directly to individual HTML elements using the `style` attribute.

2. **Internal Stylesheets:** Embed CSS rules within the `<style>` tags in the `<head>` section of an HTML document.

3. **External Stylesheets:** Create a separate CSS file and link it to your HTML document using the `<link>` tag. This approach is most recommended for maintaining clean and organized code.

**CSS Selectors and Properties**
CSS uses selectors to target HTML elements and properties to define their appearance. Here's a simple example:

```css
/* Select the <h1> element and change its color and font-size */
h1 {
    color: blue;
    font-size: 24px;
}
```

**The Box Model**
The CSS box model defines how elements are laid out on the page. Each element consists of content, padding, borders, and margins. You can control these aspects to create desired spacing and positioning.

**Classes and IDs**
Classes and IDs are used to target specific elements for styling. IDs are unique identifiers, while classes can be applied to multiple elements.

```css
/* Target elements with the "highlight" class */
.highlight {
    background-color: yellow;
}

/* Target an element with the "main-title" ID */
#main-title {
    font-size: 28px;
}
```

**Responsive Design with Media Queries**
Media queries allow you to apply different styles based on the screen size or device. This is crucial for creating responsive web pages that adapt to various devices.

```css
/* Apply styles for screens smaller than 600px */
@media (max-width: 600px) {
    body {
        font-size: 16px;
    }
}
```

**Your Task: Enhance Your Web Pages**
For this lesson's assignment, take a web page you created during the HTML course and enhance its appearance using CSS. You can apply different colors, fonts, margins, and padding to various elements. Experiment with different styles and layout techniques. Use external stylesheets to keep your code organized.

**Conclusion**
Congratulations! You've completed the first lesson in the CSS section. With CSS, you have the power to transform the appearance of your web pages and create visually appealing designs. In the next lesson, we'll explore more advanced CSS concepts, including positioning, layout, and CSS frameworks. Keep up the great work on your journey to becoming a skilled web developer!