# E-Commerce-API 🛒

E-commerce CRUD API: A RESTful API for managing product inventory, allowing Create, Read, Update, and Delete operations on products. 💼

## About ℹ️
This is an E-commerce API made using Node.Js & MongoDB. 🌐

### Steps to Use the API 🚀
1. Run `npm init` command in the project's directory.
2. Start the server using `node app.js`.
3. Open Postman.
4. Make a GET request to `localhost:3000/products`. You should see the list of products.

### Steps to Create a New Product 🆕
1. Start the server using `node app.js`.
2. Open Postman.
3. Set the URL to `localhost:3000/products/create`.
4. Select the Body tab below the URL and choose `x-www-form-urlencoded`.
5. Add `name` and `quantity` as keys and set their desired values.
6. Make a POST request.
7. If you receive the message "New product added successfully," you've done everything correctly.
8. The product is created. Check it out by making a GET request at `localhost:3000/products`.

### Steps to Delete a Product 🗑️
1. Copy the object ID of the product you want to delete.
2. Append the ID to `localhost:3000/products/`.
3. Make a DELETE request.
4. You will receive a message saying "Deleted successfully."

### Steps to Update the Quantity of a Product 🔢
1. Copy the object ID of the product whose quantity you want to update.
2. Add the ID after `localhost:3000/products/`.
3. After adding the ID, include `/update_quantity/?number={x}` in the URL, where `{x}` is the number by which you want to increase or decrease the quantity.
4. The URL should look like `localhost:3000/products/{id}/update_quantity/?number={x}`.
5. Make a POST request, and you should receive a message containing the updated product.

## Tech Stack 🚀
- Node.Js 🖥️
- MongoDB 📦
