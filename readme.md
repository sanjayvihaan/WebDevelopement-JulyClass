# Day 1
    1. Internet
    2. http/https
    3. URL Structure
    4. Creating an HTML File
        Boiler template code - shift+1 = !
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
        </head>
        <body>
            
        </body>
        </html>

        <!DOCTYPE html> - To understand with is my file.
        <html></html> - It is just a "Hyper text markup language" 
        lang="en" - En: English Content (Optional in the code base)
        head - The part where we write and add all the title and styling of the webpages or website
        <body></body> - This part is used to write all my body of the contents.


# Day 2 - 04/07
    1. Heading tags 
        h1-h6: h1 is like highest priority and important in a web pages, we need to use it only once in a single web pages.
    2. Paragraphs tags
    3. Image
        <img>
        src: Source of the image or Link
    4. lists :
        i. Ordered lists
        ii. Unordered lists
    5. Comments
        <!-- The way to write the comment-->
    6. HTML Link
        <a></a>
        href: The doc or the url to visit the page
        target: Specifies where to open the page or document

# Day 3 - 05/07
    1. Formatting Tags
    2. Favicon
    3. Div
    4. Classes
    5. Id
    6. iframes
    6. Forms

# Day 4 - 08/07
    1. HTML Colors
    2. HTML Forms
    3. HTML File Path
    4. HTML Video and Audio
    5. HTML Tables - Next Class

# Day 5 - 09/07
    1. HTML Head
    2. HTML Tables
    3. HTML Layouts
        <header> - Defines a header for the document or a section
        <nav> - To set the navigation for our webpage or website
        <section> - It will be used as a section in a document for our webpage or website
        <aside> - Like a sidebar for our page
        <footer> - It defines to have a footer in our webpage or website
    4. Basic CSS


### Project: Personal Portfolio Webpage (Day 5)

Create a personal portfolio webpage that showcases your skills, projects, and contact information. This project will incorporate all the HTML topics you've covered.

#### Project Requirements:

1. **Heading Tags (h1-h6)**
   - **Task:** Use `<h1>` for your main page title (e.g., "John Doe - Web Developer"). Use `<h2>` for section titles (e.g., "About Me", "Projects", "Contact"). Use `<h3>` to `<h6>` as needed within sections for subheadings.

2. **Paragraph Tags**
   - **Task:** Add descriptive paragraphs about yourself, your skills, and your projects.

3. **Images (`<img>`)**
   - **Task:** Include a professional profile picture using the `<img>` tag. Add images/screenshots of your projects.

4. **Lists:**
   - **Ordered Lists**
     - **Task:** Create an ordered list of your work experience or project timeline.
   - **Unordered Lists**
     - **Task:** Create an unordered list of your skills or hobbies.

5. **Comments**
   - **Task:** Use comments to document your code and explain different sections.

6. **HTML Links (`<a>`)**
   - **Task:** Add links to your social media profiles (LinkedIn, GitHub, etc.) and other relevant websites. Include links to your projects if they are hosted online.

7. **Formatting Tags**
   - **Task:** Use formatting tags to emphasize important information (e.g., `<b>` for bold text, `<i>` for italic text, `<u>` for underlined text).

8. **Favicon**
   - **Task:** Add a favicon to your webpage. Choose a small icon that represents you or your brand.

9. **Div**
   - **Task:** Use `<div>` tags to structure your webpage into sections (e.g., header, about, projects, contact).

10. **Classes and IDs**
    - **Task:** Use classes and IDs to style your sections with CSS. Apply different styles to various parts of your webpage.

11. **Iframes**
    - **Task:** Embed a map showing your location or an embedded video relevant to your work using the `<iframe>` tag.

12. **Forms**
    - **Task:** Create a contact form with fields for name, email, and message. Include a submit button.

13. **HTML Colors**
    - **Task:** Use inline styles or a separate CSS file to add colors to your text and background.

14. **HTML File Path**
    - **Task:** Use relative and absolute paths to link your images and other files correctly.

15. **HTML Video and Audio**
    - **Task:** Add a short introduction video or an audio clip about yourself or your projects.

16. **HTML Tables**
    - **Task:** Use an HTML table to display your skills or work experience in a structured format.

By completing this project, you'll have a comprehensive personal portfolio webpage that incorporates all the HTML elements you've learned.


# Day 6 - 10-07-24
    1. CSS Introduction
        a. CSS is used to make our webpage or website to look good and appeal great
        b. It is used to make our website responsive in all the devices
        c. It controls the layout of multiple web pages (website) all at once.

    2. CSS Syntax:
        selectors {property: value; property: value}
        class selector, id selector, element selector etc

        <h2 class="heading" id="head">HTML Table</h2>

        .heading {color: blue; font-size: 50px;} - Way of writing using Class Selector

        #head {color: green; font-size: 30px;} - Way of writing using Id Selector

        h2 {color: red; font-size:20px;} - Way of writing using Element Selector

    3. What are ways to write CSS
        a. Inline CSS
        b. Internal CSS
        c. External CSS - 

# Day 7 - 11-07-24
    1. Way of writing CSS:
        a. External CSS
    2. CSS Comments
        /* This is the way to write the css comments */
    3. CSS Backgrounds
        a. background-color
        b. background-image
        c. background-repeat
        d. background-position
        e. background (shorthand)
        f. background-attachment
        
    4. CSS Borders : The css borders properties allow us to specify the style, width and color for an element's border
        a. Border width
        b. Border color
        c. Border sides
        d. Border Shorthand
        e. Rounded borders
        f. border-style:
            solid - Defines a solid border
            dotted - Defines a dotted border
            dashed - Defines a dashed border
            double - Defines a double border
            groove - Defines a 3D grooved border. The effect depends on the border-color value
            ridge - Defines a 3D ridged border. The effect depends on the border-color value
            inset - Defines a 3D inset border. The effect depends on the border-color value
            outset - Defines a 3D outset border. The effect depends on the border-color value
            none - Defines no border
            hidden - Defines a hidden border
    5. CSS Margin

