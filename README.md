## Flask Application Design for an E-commerce Website

### HTML Files

- **home.html:** Displays the home page with product categories.
- **product_list.html:** Lists products within a specific category.
- **product_detail.html:** Displays product details and allows users to add it to the cart.
- **cart.html:** Displays the user's current cart and checkout options.
- **checkout.html:** Handles the checkout process, including payment and order confirmation.

### Routes

**Main Routes:**

- **@app.route('/')**: Home page
- **@app.route('/category/<category_id>'**: Product list page for a specific category
- **@app.route('/product/<product_id>'**: Product detail page

**Cart Routes:**

- **@app.route('/add_to_cart'**: Adds a product to the user's cart
- **@app.route('/get_cart'**: Retrieves the user's current cart
- **@app.route('/checkout'**: Checkout page

**Payment Routes:**

- **@app.route('/payment'**: Handles payment processing
- **@app.route('/confirmation'**: Order confirmation page

**Additional Routes:**

- **@app.route('/about'**: About page
- **@app.route('/contact'**: Contact page