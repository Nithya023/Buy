Simple E-commerce Landing Page and Thank You Page
This repository contains two simple HTML files designed to create a basic e-commerce presence: a product landing page and a purchase confirmation (thank you) page.

🚀 Project Overview
index.html (Landing Page): Showcases two products with descriptions, prices, and "Buy Now" buttons. The buttons are linked to open a new page (currently a placeholder).

thank-you.html (Thank You Page): A confirmation page displayed after a successful purchase, offering options to continue shopping or view order details.

Both pages are designed to be responsive and visually appealing using Tailwind CSS.

📁 Files
index.html: The main landing page.

thank-you.html: The thank you page displayed after a purchase.

🛠️ Setup and Usage
These are static HTML files and do not require a server to run for basic viewing.

Download/Copy: Save both index.html and thank-you.html files to the same directory on your computer.

Open in Browser:

To view the landing page, simply open index.html in your web browser (e.g., by double-clicking it).

To view the thank you page, open thank-you.html in your web browser.

Linking the Pages:

To connect the "Buy Now" buttons on the index.html page to the thank-you.html page, you would typically modify the href attribute of the <a> tag inside the "Buy Now" buttons on the landing page.

In index.html, change:

<a href="#" target="_blank" class="buy-button-link">
    Buy Now
</a>

to:

<a href="thank-you.html" target="_blank" class="buy-button-link">
    Buy Now
</a>

This will open the thank-you.html page in a new tab when the "Buy Now" button is clicked.

✨ Customization
You can easily customize these pages:

Product Details (index.html):

Change product names, descriptions, prices, and placeholder image URLs (src attribute of <img>).

Update the href attributes of the "Buy Now" buttons to point to your actual product purchase URLs.

Text and Messages (index.html, thank-you.html):

Modify any of the text content within the <h1>, <p>, <h2>, and button elements.

Styling:

Both pages use Tailwind CSS. You can modify the existing Tailwind classes directly in the HTML to change colors, spacing, fonts, and layout.

For more advanced custom styles, you can add additional CSS rules within the <style> tags in the <head> section of each HTML file.

🌐 Technologies Used
HTML5: For the page structure.

Tailwind CSS: A utility-first CSS framework for rapid UI development and responsiveness.

Google Fonts (Inter): For a modern and clean typeface.
