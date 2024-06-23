##Introduction
This report covers  a simple e-commerce website. The site allows users to browse products, view details, add items to their cart, and proceed to checkout. I used HTML, CSS, and JavaScript for the site and got product data from the Fake Store API.
Project Overview
  •	Home Page (index.html): Shows a list of products from the API. Users can view product details, add items to their cart, or go to checkout.
  •	Contact Page (contact.html): Includes a form for users to send messages.
  •	Checkout Page (checkout.html): Allows users to review and complete their purchase.

##Development Steps
1. Creating the Header
I started by making the header, which has the navigation links and a cart icon:
  •	Set up a navigation bar with links to the home and contact pages.
  •	Added a cart icon that shows the number of items in the cart.
  •	Styled the header to make it look clear and neat.

2. Displaying the Product List
Next, I worked on showing the products on the home page:
  •	Created a section to list the products fetched from the Fake Store API.
  •	Designed each product’s display, including the image, title, price, and buttons for more details and adding to the cart.

3. Product Detail View
To let users see more about each product:
  •	Made a hidden section that shows more details about a product when requested.
  •	Set up a way to show extra information like a description and a larger image in this section.

4. Adding Shopping Cart Features
After the product details, I added the shopping cart:
  •	Designed a sidebar to show items added to the cart, along with their images, titles, and prices.
  •	Added features to update the cart’s contents and the item count.

5. Building the Contact Page
For the contact page:
  •	Created a form where users can enter their name, email, and message.
  •	Added a simple handler to show a success message when the form is submitted and redirect users back to the home page.

6. Developing the Checkout Page
   To complete the purchase process:
  •	Created a checkout page that shows the details of the items in the cart.
  •	Added a step for users to confirm their purchase, then show a thank you message and return to the home page.

##Challenges and Solutions
	•	Fetching Data from API: I faced issues with getting product data correctly, which I solved by debugging the API calls and handling the timing of data loading.
	•	Updating the Page Dynamically: Making sure the page updates smoothly, especially for product details and the cart, required careful handling of changes and event listeners.

##Resources
The code for this feature was gathered from lessons and various resources, including:
  •	[MDN Web Docs]
  •	[Wes Bos]
  •	[w3schools]
  •	Various tutorials and articles found through Google.

##Conclusion
Building this e-commerce site was a good learning experience in creating a functional website with HTML, CSS, and JavaScript. Using the Fake Store API and adding key e-commerce features helped create a basic online shopping experience. The site lets users browse products, manage a shopping cart, and complete a purchase, serving as a simple starting point for future projects.

