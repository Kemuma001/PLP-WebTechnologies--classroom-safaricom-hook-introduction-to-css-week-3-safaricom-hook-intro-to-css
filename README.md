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
