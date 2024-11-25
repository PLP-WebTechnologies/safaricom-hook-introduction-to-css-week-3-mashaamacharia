## **🎓 CSS Basics Assignment**  

### **Assignment Title**  
**"Mastering CSS Basics: Styling Your First Web Page"**  

---

### **📋 Objectives**  
- Understand the use of CSS selectors, properties, and values.  
- Apply inline, internal, and external CSS to style web pages.  
- Utilize basic CSS properties to control colors, fonts, alignment, padding, and margins.  

---

### **📂 Assignment Tasks**  

#### **Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)**  
1. Create an HTML file with at least three different types of elements (e.g., `<h1>`, `<p>`, `<div>`).  
2. Style these elements using:  
   - **Element Selector**: Change the font size of all headings.  
   - **Class Selector**: Apply a background color to specific sections.  
   - **ID Selector**: Add a border to an element with a unique ID.  

---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Elements</title>
    <style>
        /* Element Selector: Style all headings */
        h1 {
            font-size: 36px;
            color: #333;
        }

        /* Class Selector: Apply background color to specific sections */
        .highlight-section {
            background-color: #f0f8ff;
            padding: 20px;
            border-radius: 8px;
        }

        /* ID Selector: Add a border to an element with a unique ID */
        #unique-div {
            border: 2px solid #007bff;
            padding: 15px;
            margin-top: 20px;
            background-color: #e9f7fd;
        }
    </style>
</head>
<body>

    <!-- Heading (Element Selector) -->
    <h1>Welcome to the Styled Page!</h1>

    <!-- Paragraph -->
    <p>This is a simple webpage with different types of HTML elements styled using CSS selectors.</p>

    <!-- Section with Class Selector -->
    <div class="highlight-section">
        <h2>Special Section</h2>
        <p>This section has a background color applied using a class selector.</p>
    </div>

    <!-- Section with ID Selector -->
    <div id="unique-div">
        <h2>Unique Styled Section</h2>
        <p>This section has a border applied using an ID selector.</p>
    </div>

</body>
</html>


#### **Part 2: Inline, Internal, and External CSS (30 Points)**  
1. Use **inline CSS** to style one element (e.g., change the text color).  
2. Add **internal CSS** in the `<style>` tag within the `<head>` section to style at least three elements.  
3. Create a separate **external CSS file** and link it to your HTML. Use it to:  
   - Change the background color of the webpage.  
   - Style links with hover effects.  

---

#### **Part 3: Basic Styling Properties (50 Points)**  
1. Apply the following styles:  
   - **Colors**: Set text and background colors for different elements.  
   - **Font Styles**: Change the font family, size, and weight of text.  
   - **Text Alignment**: Center-align, left-align, or justify text in paragraphs.  
   - **Spacing**: Add padding and margin to elements for proper spacing.  

2. Create a **simple card component** using these styles:  
   - A heading for the card title.  
   - A paragraph with some description.  
   - Add padding inside the card and a margin around it.  
   - Use a light background color and a subtle border.  

```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Example</title>
    
    <!-- Internal CSS -->
    <style>
        /* Internal CSS: Styling for headings, paragraphs, and card */
        h1 {
            color: #4CAF50;
            font-family: 'Arial', sans-serif;
            text-align: center;
        }

        p {
            font-family: 'Georgia', serif;
            font-size: 16px;
            line-height: 1.5;
            text-align: justify;
            color: #333;
        }

        .card {
            background-color: #f9f9f9;
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            max-width: 500px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
    </style>

    <!-- External CSS File Link -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Inline CSS: Styling for this paragraph -->
    <p style="color: #ff6347; text-align: center;">This paragraph uses inline CSS to change the text color and center-align the text.</p>

    <!-- Heading for the page -->
    <h1>Welcome to the CSS Styling Example!</h1>

    <!-- Card Component -->
    <div class="card">
        <h2>Card Title</h2>
        <p>This is a simple card component that includes a title and a description. It uses padding, margin, a light background, and a subtle border to create a visually appealing container for content.</p>
    </div>

    <!-- A simple link to demonstrate external CSS link styling -->
    <a href="#" class="styled-link">Click me for more info</a>

</body>
</html>



/* External CSS: This file is linked to the HTML file */

/* Set background color for the entire webpage */
body {
    background-color: #f0f0f0;
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

/* Style links and add hover effect */
.styled-link {
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
}

.styled-link:hover {
    color: #0056b3;
    text-decoration: underline;
}


This assignment will solidify your CSS basics while giving you a chance to style your first webpage creatively. Good luck and happy styling! 🎨🚀
