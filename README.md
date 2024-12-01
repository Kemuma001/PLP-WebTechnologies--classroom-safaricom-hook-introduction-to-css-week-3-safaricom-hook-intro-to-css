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

         
     EXTERNAL CSS
  
         body {
              background-color: #f0f8ff;
              margin: 0;
              padding: 0;
               }
     a:hover {
             color: #ff4500;
             text-decoration: underline;
            }

            
            
Part 3: Basic Styling Properties (50 Points)


                   body {
                        background-color: #f0f8ff;
                        margin: 0;
                       padding: 0;
                      color: #333;
                          }

             .content-section {
                    background-color: #ffffff;
                    border: 1px solid #ddd;
                    padding: 20px;
                    margin: 20px auto;
                   width: 80%;
                    border-radius: 8px;
                  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
                                }
             a {
                  color: #007bff;
                  text-decoration: none;
                  font-weight: bold;
                     }

            a:hover {
                    color: #0056b3;
                    text-decoration: underline;
                         }



2. Create a simple card component using these styles:
           A heading for the card title.
           A paragraph with some description.
           Add padding inside the card and a margin around it.
           Use a light background color and a subtle border.


      <!DOCTYPE html>
            <html lang="en">
             <head>
             <meta charset="UTF-8">
             <meta name="viewport" content="width=device-width, initial-scale=1.0">
             <title>Card Component</title>
                    <style>

                body {
                    font-family: Arial, sans-serif;
                    background-color: hsl(330, 81%, 51%);
                    margin: 0;
                    padding: 20px;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    min-height: 100vh;
                        }

                    .card {
                        background-color: hsl(115, 88%, 50%);
                        border: 1px solid hsl(0, 96%, 50%);
                        border-radius: 8px;
                        padding: 20px;
                        margin: 20px;
                        box-shadow: 0 4px 8px rgba(67, 209, 31, 0.1);
                        max-width: 300px;
                        text-align: center;
                                }

                    .card-title {
                            font-size: 24px;
                            font-weight: bold;
                             color: #333;
                               margin-bottom: 10px;
                                    }

                    .card-description {
                                font-size: 16px;
                                color: #555;
                                line-height: 1.5;
                                    }
            </style>
            </head>
        <body>
            <div class="card">
                <h2 class="card-title">Card Title</h2>
                <p class="card-description">
                This is a simple card component. It has a title, a description, and a neat design with padding, margin, and a light border.
                </p>
            </div>
        </body>
            </html>
