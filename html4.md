**Introduction to HTML: Lesson 4 - Styling with CSS**

Welcome to another exciting lesson in our HTML course! In this lesson, we'll explore the world of Cascading Style Sheets (CSS) and learn how to enhance the visual appeal of your web pages.

**Understanding CSS**
CSS is a powerful language used to control the presentation and layout of HTML elements. With CSS, you can apply styles such as colors, fonts, spacing, and positioning to make your web pages look visually appealing and professional.

**Inline Styles**
You can apply styles directly to HTML elements using inline styles. An inline style is defined using the `style` attribute within an HTML tag.

```html
<p style="color: blue; font-size: 18px;">This is a styled paragraph.</p>
```

**Internal Stylesheets**
Internal stylesheets are placed within the `<head>` section of an HTML document. You define styles using the `<style>` tag and the CSS syntax.

```html
<head>
    <style>
        p {
            color: green;
            font-size: 16px;
        }
    </style>
</head>
```

**External Stylesheets**
External stylesheets are separate CSS files linked to your HTML document using the `<link>` tag. This method allows you to apply styles consistently across multiple pages.

```html
<head>
    <link rel="stylesheet" href="styles.css">
</head>
```

**Selectors and Properties**
CSS uses selectors to target HTML elements and properties to define their appearance. Here's an example of a rule:

```css
p {
    color: purple;
    font-size: 20px;
}
```

**Box Model and Layout**
The CSS box model defines how elements are laid out on the page, comprising content, padding, borders, and margins. You can control the spacing and arrangement of elements using properties like `margin`, `padding`, `border`, and `display`.

**Your Task: Styling Your Page**
For this lesson's assignment, create an external CSS file named `styles.css`. Link this stylesheet to your existing HTML pages from the previous lessons. Apply styles to various elements such as headings, paragraphs, lists, and links. Experiment with changing colors, fonts, margins, and more to make your pages visually appealing.

**Conclusion**
Congratulations! You've completed the fourth lesson of our HTML course. You've gained a solid understanding of how to style HTML elements using CSS, enhancing the aesthetics and layout of your web pages. In the next lesson, we'll explore responsive design and how to create web pages that adapt to different screen sizes. Keep up the fantastic work on your web development journey!