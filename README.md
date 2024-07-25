# shopify-add-to-cart
A simple tool to create a url to provide customers to add to cart

This tutorial code requires a little bit of copy and paste in your Shopify backend to make it work but should take about 5 minutes no more.

For a visual overview and full details, see our article at https://onescales.com/blogs/main/shopify-add-to-cart and our youtube video at https://www.youtube.com/watch?v=E9DC631wYuU

# Steps

1. Login to Shopify Backend
2. Customize your theme and add a new "page template" called "Add to Cart" based on "Default Page".
3. In this "Add to Cart" page template add a new section called "Custom Liquid" and copy the code from https://github.com/onescales/shopify-add-to-cart/blob/main/add-to-cart.liquid and save.
4. Create New Page (for example - Add to Cart) and Select "theme template" "Add to Cart"
5. Visit "Add to Cart" page and use the form to get a url of your cart
- Checkbox the product you want to add to cart for and specify the quantity. Note you will be able to select only 1 product for the tool to work.
- Click on "Build URL".
- Grab either the QR code or the url via copy and provide to your customers. Note you can right click and "save as image" the qr code to use later.
6. Start Using It. Enjoy!

# Additional Notes
- Currently limited to 1000 products. If you have more than 1000 products in your catalog, you will need to customize code on your end.
- If customer had an existing cart already, it will add to the cart.
- Note that the above instructions are to create a new page and add liquid code. These instructions will create a public live page which some of you probably don't want to showcase to the world so you will have to add a password to it or use the liquid in this repo to do it in your own protected way. You can also make visibility "hidden" and use it as a logged in admin by clicking on view page button.
- QR Code generated is using quickchart.io
- All code and instructions are as is. By reading this repository, readme or any code, you acknowledge that you are solely responsible for your own doings.

Hope you liked this!

# Suggestions, Comments and Contact
If you have any suggestions, comments, insight or just want to say hi, thanks or share your experience, you can contact us at:
- Our WebSite: https://onescales.com/
- Contact Us: https://onescales.com/pages/contact
- Youtube Channel: https://www.youtube.com/@onescales
- Twitter/X: https://twitter.com/one_scales
- LinkedIn: https://www.linkedin.com/company/one-scales/






