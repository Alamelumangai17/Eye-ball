# Eye-ball
This is an HTML document that creates a simple "Eye Movement" effect using HTML, CSS, and JavaScript. Here's a description of its components:

Steps to run the code:

step 1. HTML Structure:
   - The document starts with the usual HTML5 structure, including the <!DOCTYPE html> declaration.
   - It sets the document's language to English (<html lang="en">).
   - Inside the <head> section, there are meta tags for character encoding and viewport settings, as well as a title for the page.
   - The <style> section contains CSS styles for the page's elements.
   - The <body> section contains the content of the webpage.

step 2. CSS Styles:
   - The CSS styles define the appearance of the "Eye Movement" effect.
   - It sets the background color of the <body> to a blueish color (#3172a4).
   - The .container class centers its contents both vertically and horizontally.
   - The .eye class defines the appearance of the eye shape, a white circle with a border.
   - The .eyeball class represents the black pupil of the eye.

step 3. JavaScript:
   - JavaScript is used to create the eye movement effect.
   - It selects the elements with the class "eyeball" and stores them in the eyeballs variable.
   - An event listener is added to the document for the "mousemove" event.
   - When the mouse is moved, the event's clientX and clientY properties are used to calculate the new position (x and y) for the eyeballs relative to the window's width and height.
   - The position of both eyeballs is updated to follow the mouse cursor by changing their left and top CSS properties.
    
Future Implementations of the code

Overall, this code creates two eyes that follow the movement of the mouse cursor, creating a fun and interactive "Eye Movement" effect on the webpage.
