Updated (04/10/2026) - Raiden:

Added functionality to the details, checkout, and cart page.
Now you can add pizzas to the cart from the details.html page and they will show up on the cart.html and checkout.html page

Also added a dynamic 'Last Updated' date in the footer that shows when each page was last updated.

To-do list:
-Find a way to calculate prices for each pizza item based on their type, size, and quantity
-Make images and content fit update for all screen sizes
-Make the pages more appealing (especially the index.html page)
-Add dynamic pseudo-classes for the forms to validate input
-Fix contact and checkout form logic for when you press the submit button


Updated (04/11/2026) - Kyle:

Added some general styling to the pages. Added transitions for the images in the menu page. Added qr code and location image to contact.html. Filled in some placeholder text on index.html.


Updated (04/13/2026) - Raiden:

Organized files into /assets and /css subfolders
Added a calculatePrice() function to the cart.html page, so that it displays the correct price for the type and size of the pizza.
Added a new section to the index.html page.
Fixed an issue where the quantity of pizza added could be NaN.
Updated pricing table on details.html to reflect the new pizza pricing. 
Added an alert() to give feedback to user when they add pizza to their shopping cart.
Reorganized checkout.html page.

To-do list:
-Properly display order details on checkout.html, which includes the items in the order, the price of the items, the total before taxes, the taxes, and the net total of the order.
-Make images and content fit update for all screen sizes.
-Add dynamic pseudo-classes to the forms to validate input.
-Fix contact and checkout form logic for when you press the submit button, so that the success message and arrival time only show when the user enters information into all the required input fields.
-Add a way to remove items from the shopping cart.

Missing Requirements from Final Project Guidelines:

  HTML5
  -All images must include descriptive alt attributes.
  -Use appropriate special characters (HTML entities).
  -Include appropriate <meta> tags.

  CSS3
  -Use dynamic pseudo-classes to highlight hyperlink states: :link, :visited, :active, :hover, and :focus. Also use two structural pseudo-classes: :first-of-type and :last-of-type.
  -Use CSS background styles including: background-size, padding, margins, borders, border-radius (rounded corners), and an appropriate border style.
  -Use CSS text shadows and box shadows.
  -Apply CSS opacity to at least two images to make them appear semi-transparent.

  Web Form 
  -Apply inline form validation using the :focus pseudo-class on appropriate form elements.

  Responsive Design
  -Implement responsive design using topics covered on class.
  -All images must be responsive (e.g., use max-width: 100% or similar techniques).
  -The web form must also be responsive across different screen sizes.


  Updated (04/13/2026) - Raiden:

  Validated webpages through W3C Validation Checker, and fixed most of the errors.
  Added alt attributes to all <img> tags.
  Added <meta charset="utf-8"> and <html lang="en-CA"> to all pages.
  Added one semi-transparent image as index.html background.
  Customized borders of images on index.html using border-radius and border-style.
  Added box shadows to images on index.html.
  Added text shadows on paragraph text on index.html.
  Added a copyright symbol alongside some text in the footer of all pages (HTML entity).
  Added an outline to the navigation bar and footer.
