**Introduction to HTML: Lesson 2 - Exploring Common HTML Elements**

Welcome back to our HTML course! In this lesson, we will dive deeper into HTML elements and their various uses. We'll explore some common elements that allow you to structure and format your content to create engaging web pages.

**HTML Elements for Text and Headings**
HTML provides a range of elements to structure your text content:

1. **Headings (`<h1>` to `<h6>`):** Headings are used to define the hierarchy of content. `<h1>` is the highest level, representing the main heading, while `<h6>` is the lowest level.

2. **Paragraphs (`<p>`):** The `<p>` element is used to create paragraphs of text.

3. **Bold (`<b>`) and Italic (`<i>`):** The `<b>` element makes text bold, while the `<i>` element italicizes text.

**HTML Elements for Lists**
Lists help organize content in a structured manner:

1. **Ordered List (`<ol>`):** Use `<ol>` to create an ordered (numbered) list.

2. **Unordered List (`<ul>`):** `<ul>` creates an unordered (bullet-point) list.

3. **List Item (`<li>`):** Inside `<ol>` or `<ul>`, use `<li>` to define each list item.

**HTML Elements for Links and Images**
Adding links and images enriches your content:

1. **Anchor (`<a>`):** The `<a>` element creates hyperlinks. Use the `href` attribute to specify the URL.

2. **Image (`<img>`):** The `<img>` element displays images. Set the `src` attribute to the image URL.

**HTML Elements for Semantic Structure**
HTML5 introduced semantic elements for better content structure:

1. **Header (`<header>`):** Represents the header of a section or page.

2. **Nav (`<nav>`):** Defines navigation links.

3. **Article (`<article>`):** Represents independent, self-contained content.

4. **Section (`<section>`):** Defines a section of content.

5. **Footer (`<footer>`):** Represents the footer of a section or page.

**Putting it All Together**
Let's create a more comprehensive example using the elements we've covered:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Exploring HTML Elements</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section>
        <article>
            <h2>About Me</h2>
            <p>I'm passionate about web development and love creating engaging user experiences.</p>
            <p>Feel free to explore my projects and get in touch!</p>
        </article>
        
        <article>
            <h2>My Projects</h2>
            <ul>
                <li><a href="project1.html">Project 1</a></li>
                <li><a href="project2.html">Project 2</a></li>
            </ul>
        </article>
    </section>
    
    <footer>
        <p>Contact: <a href="mailto:info@example.com">info@example.com</a></p>
    </footer>
</body>
</html>
```

**Your Task: Building a Personal Page**
For this lesson's assignment, create an HTML file named `profile.html`. Build a simple webpage that represents your profile. Use headings, paragraphs, lists, links, and at least one image to describe yourself, your interests, and any projects you'd like to showcase. Apply the semantic elements to structure your content.

**Conclusion**
Great job! You've completed the second lesson of our HTML course. You've learned how to use various HTML elements to structure and format your content, making your web pages more organized and visually appealing. In the next lesson, we'll cover forms and input elements, enabling user interaction on your web pages. Keep up the fantastic work!