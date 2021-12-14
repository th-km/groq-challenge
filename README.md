# GROQ Challenge

## Setup

1. Run `npx sanity init`
2. Select `create new project`
3. Use the `default` dataset
4. Select the `E-commerce` template with sample data
5. Once the studio is initialized, `cd` into the studio and run `sanity start`
6. Go to the Vision pane and select the `v2021-03-25` API version

## Challenge

1. Get all data.
2. Get the first result.
3. Get all products.
4. Get the first 10 products.
5. Get all products title, ordered alphabetically in ascending order.
6. Get all products with a price superior to 10.
7. Get all products with the category "Chocolate".
8. Get all products, and add a "product_description" property with the product and vendor title, separated by a comma.
9. Get all products, and add a "rating" property with a value set to "expensive" if the product price is superior to 10 or "affordable" if the price is lower.
10. Get all products, and add a "custom_slug" property with the prefix "/good-deal/" if the product price is inferior to 5, otherwise display the current slug.
11. Get all products, and add an "early_bird_price" property with a product price discounted by 25%. The new price should be rounded.
12. Get all products, and add an "image_cover" property with the first product image.
13. Get all vendors, and add a "brand_color" property with the dominant background color of the vendor logo.
14. Get all vendors, and add a "related_products" property with their related products title.
