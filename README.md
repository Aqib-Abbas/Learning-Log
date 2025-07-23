**LEARNING LOG**

Day 1: 03-07-2025
Thursday

Topic Covered:

heading, paragraph. line break

1. <!DOCTYPE html> – Declares the document type and version as HTML5.


2. <html> – Defines the root of an HTML document.


3. <head> – Contains metadata, links, and title for the document.


4. <title> – Sets the title of the web page shown in the browser tab.


5. <body> – Contains the visible content of the web page.


6. <h1> to <h6> – Define headings, with <h1> being the largest and <h6> the smallest.


7. <p> – Defines a paragraph of text.

8. <br> - Inserts a line break within text or element
   

9.📘 Day 2:04-07-2025
   Friday

1. <a> – Creates a hyperlink to another page or URL.


2. <img> – Embeds an image in the web page.


3. <ul> – Defines an unordered (bulleted) list.


4. <ol> – Defines an ordered (numbered) list.


5. <li> – Defines a list item inside <ul> or <ol>.


6. <div> – Defines a division or section in an HTML document.


7. <strong> – Makes text bold and emphasizes importance.


8. <input> – Creates an input field for user data in forms.




📘 Day 3:09-07-2025
    Wednesday


1. <a> – Creates a hyperlink to another page or URL.


2. <img> – Embeds an image in the web page.


3. <ul> – Defines an unordered (bulleted) list.


4. <ol> – Defines an ordered (numbered) list.


5. <li> – Defines a list item inside <ul> or <ol>.


6. <div> – Defines a division or section in an HTML document.


7. <strong> – Makes text bold and emphasizes importance.


8. <input> – Creates an input field for user data in forms.

Sure! Here's your Day 4 Learning Log with 6 tags:


---

📘 Day 4 – 10-07-2025
   Thursday

1. <header> – Defines the top section of a page, like a logo or title.


2. <nav> – Contains navigation links.


3. <main> – Represents the main content of the page.


4. <section> – Groups related content together.


5. <article> – Represents independent content like blog posts.


6. <footer> – Defines the bottom section like copyright or links.



Sure! Here's your Day 5 Learning Log focused only on HTML form-related tags:


---

📘 Day 5 – 11-07-2025
    Friday

1. <form> – Creates a form to collect user input.


2. <input> – Allows users to enter data (text, number, etc.).


3. <label> – Adds a text label for a form element.


4. <textarea> – Allows multi-line text input.


5. <select> – Creates a drop-down list.


6. <option> – Defines choices inside a drop-down (<select>).


Here’s your Day 6 Learning Log focused on Accessibility Basics in HTML:


---

📘 Day 6 – 12-07-2025
   Saturday

   
1. alt attribute – Provides alternative text for images, helpful for screen readers.


2. <label for=""> – Links a label to a specific form input to improve accessibility.


3. Proper form structure – Use <form>, <label>, and associated inputs correctly for assistive technologies.
4. <form>
      <label for=" ">
         <input type=" " id=" " name=" ">
      </label><br>
      <button type=" "> </button>
   </form>
==========================================================================================================================================================

Day 7:  
16 - 07 - 2025 (Wednesday) 
Topic: CSS Syntax and Selectors

The general syntax of CSS is: selector { property: value; }

Selectors are used to select HTML elements to apply specific styles. There are three main types: ID, Class, and Element selectors.

→ ID Selector: Targets a unique element. It is written using #, for example: #header.

→ Class Selector: Targets multiple elements with the same class. It is written using ., for example: .box.

→ Element Selector: Directly targets HTML tags such as <h1>, <p>, <div>, etc.

Selectors help us apply different styles to specific parts of the webpage effectively.


Day 8:  
17 - 07 - 2025 (Thursday)  
Topic: CSS Colors, Fonts, and Units

In CSS, we use different properties to style text and layout using colors, fonts, and measurement units.

→ Colors: CSS supports color names (red, blue), HEX codes (#ff0000), RGB (rgb(255,0,0)), and HSL formats.

→ Fonts: We use font-family to apply fonts like Arial, Verdana, or Google Fonts. We can also set bold or italic using font-weight and font-style.

→ Units:
- px (pixels): Fixed-size units.
- em: Relative to the parent’s font size.
- rem: Relative to the root element’s font size.
- % (percent): Relative to the parent container size.

Using the right fonts, colors, and units improves both the *appearance* and *responsiveness* of a web page.


Day 9:  
18 - 07 - 2025 (Friday)  
Topic: CSS Box Model

The CSS Box Model describes how every HTML element is structured and spaced in the layout.

It consists of the following parts (from inside out):

→ Content: The actual text or image inside the element.  
→ Padding: Space between the content and the border (inside the box).  
→ Border: The edge surrounding the padding and content.  
→ Margin: Space outside the element that separates it from other elements.

Each part can be styled using CSS properties like margin, padding, border, and width/height.

Understanding the box model is essential for controlling *spacing, **alignment, and **layout design* effectively.



Day 10:  
19 - 07 - 2025 (Saturday)  
Topic: CSS Display Types

The `display` property in CSS controls how an element is rendered on the page.

→ block: Takes up the full width available (e.g., <div>, <p>). Starts on a new line.

→ inline: Takes up only as much width as needed (e.g., <span>, <a>). Stays within the line.

→ inline-block: Behaves like inline but allows setting width, height, padding, and margin.

→ flex: Enables a flexible box layout. It allows easy alignment and distribution of items using `display: flex`.

→ grid: Provides a two-dimensional layout system for arranging items in rows and columns using `display: grid`.

Choosing the right display type helps control element behavior and structure the layout properly.



Day 11:  
21 - 07 - 2025 (Monday)  
Topic: CSS Flexbox Layout

Flexbox is a one-dimensional layout model used to align and distribute space among items in a container.

To use Flexbox, we set the container’s `display` to `flex`:
→ display: flex; – enables flexbox on the container.

Main properties for layout control:
→ justify-content: Aligns items horizontally (e.g., center, space-between, space-around).  
→ align-items: Aligns items vertically (e.g., center, flex-start, flex-end).  
→ flex-direction: Sets the direction of the flex items (row, column).  
→ gap: Adds spacing between items.

Flexbox helps build responsive layouts with clean alignment and spacing, especially for navigation bars and cards.



Day 12:  
22 - 07 - 2025 (Tuesday)  
Topic: CSS Grid Layout

CSS Grid is a two-dimensional layout system used to arrange items in rows and columns with precision.

To activate Grid, we use: `display: grid;` on the container.

Key properties used in Grid layout:
→ grid-template-columns: Defines the number and size of columns (e.g., 1fr 1fr for two equal columns).  
→ grid-template-rows: Defines row heights.  
→ gap: Sets space between rows and columns.  
→ grid-column / grid-row: Specifies how many columns or rows an item should span.  
→ place-items: Shorthand to align items both vertically and horizontally (like `center`, `start`, `end`).

CSS Grid is ideal for creating complex layouts like galleries, dashboards, and structured page sections.



Day 13:  
23 - 07 - 2025 (Wednesday)  
Topic: Media Queries (Responsive Design)

Media queries allow us to apply different CSS styles based on the device’s screen size or resolution.

Syntax example:  
@media (max-width: 768px) {  
 body { font-size: 14px; }  
}

Key uses of media queries:
→ Adjust font size, layout, or spacing for mobile devices.  
→ Create mobile-first designs that scale up for larger screens.  
→ Use breakpoints like 600px (mobile), 768px (tablet), and 1024px+ (desktop).

Media queries help create responsive websites that look good on all devices, from phones to large screens.
