# Product Management Application

This is a simple product management application built with Node.js, Express, MongoDB, and EJS for templating.

## Project Structure

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd server
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the server:
    ```sh
    npm start
    ```

## Usage

1. Ensure MongoDB is running on your machine. The application connects to MongoDB at `mongodb://127.0.0.1:27017/product`.

2. Open your browser and navigate to `http://localhost:8000`.

3. You can perform the following actions:
    - View all products at `/products`.
    - Add a new product at `/products/new`.
    - View details of a specific product at `/products/:id`.
    - Edit a product at `/products/:id/edit`.
    - Delete a product by clicking the delete button on the product detail page.

## Project Files

- [app.js](http://_vscodecontentref_/10): Main application file where the Express server is set up and routes are defined.
- [Product.js](http://_vscodecontentref_/11): Mongoose schema and model for the Product.
- [style.css](http://_vscodecontentref_/12): CSS file for styling the application.
- [views](http://_vscodecontentref_/13): EJS templates for rendering the views.
    - [index.ejs](http://_vscodecontentref_/14): Template for displaying all products.
    - [new.ejs](http://_vscodecontentref_/15): Template for adding a new product.
    - [edit.ejs](http://_vscodecontentref_/16): Template for editing an existing product.
    - [show.ejs](http://_vscodecontentref_/17): Template for displaying a single product's details.
    - [header.ejs](http://_vscodecontentref_/18): Header partial template.
    - [footer.ejs](http://_vscodecontentref_/19): Footer partial template.

## Dependencies

- [express](http://_vscodecontentref_/20): Web framework for Node.js.
- [mongoose](http://_vscodecontentref_/21): MongoDB object modeling tool.
- `ejs`: Embedded JavaScript templating.
- `method-override`: Middleware to support HTTP verbs like PUT and DELETE.
- `nodemon`: Utility that monitors for any changes in your source and automatically restarts your server.

## License

This project is licensed under the ISC License.
