1.Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)
    Create an HTML file with at least three different types of elements (e.g., <h1>, <p>, <div>).
    Style these elements using:
    Element Selector: Change the font size of all headings.
    Class Selector: Apply a background color to specific sections.
    ID Selector: Add a border to an element with a unique ID.


             <!DOCTYPE html>
               <html lang="en">
                 <head>
                   <meta charset="UTF-8">
                   <meta name="viewport" content="width=device-width, initial-scale=1.0">
                   <title>Styled Elements Example</title>
                   <style>
                        h1, h2, h3 {
                               font-size: 24px;
                              color: #333;
                                    }
              .highlight {
               background-color: #f0f8ff;
               padding: 10px;
               border-radius: 5px;
                       }

              #unique-section {
              border: 2px solid #4caf50;
              padding: 10px;
             margin: 10px 0;
                    }
              </style>
                     </head>
                <body>
            <h1>Welcome to My Web Page</h1>
             <p>This is a paragraph describing the purpose of the webpage.</p>

             <div class="highlight">
             <h2>About Us</h2>
             <p>This section gives an overview of what we do.</p>
             </div>

           <div id="unique-section">
          <h3>Contact Us</h3>
          <p>Reach out via email: example@example.com</p>
           </div>
           </body>
            </html>

            
Part 2: Inline, Internal, and External CSS (30 Points)
       Use inline CSS to style one element (e.g., change the text color).
      Add internal CSS in the <style> tag within the <head> section to style at least three elements.
      Create a separate external CSS file and link it to your HTML. Use it to:
      Change the background color of the webpage.
       Style links with hover effects.

       <!DOCTYPE html>
           <html lang="en">
            <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
             <title>CSS Styling Example</title>
             <!-- Link to the external CSS file -->
             <link rel="stylesheet" href="styles.css">
              <style>
        body {
            font-family: Arial, sans-serif;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
        }

        p {
            font-size: 18px;
            line-height: 1.5;
        }

        nav a {
            text-decoration: none;
            color: #4caf50;
        }
       </style>
           </head>
                  <body>
              <!-- Inline CSS: Change text color -->
          <h1 style="color: darkblue;">Welcome to My Styled Page</h1>

    <nav>
        <a href="#about">About Us</a> |
        <a href="#contact">Contact Us</a>
    </nav>

    <div id="about">
        <h2>About Us</h2>
        <p>This section provides information about our mission and values.</p>
    </div>

    <div id="contact">
        <h2>Contact Us</h2>
        <p>Feel free to reach out via email: <a href="mailto:example@example.com">example@example.com</a></p>
    </div>
         </body>
         </html>




