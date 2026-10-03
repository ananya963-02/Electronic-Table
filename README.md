# Electronic-TableElectronics Product Table

A simple HTML and CSS project that displays a list of electronic products in a structured and visually styled table. The table includes product names, quantities, per-unit prices, individual amounts, and a total amount.

Features

- 📊 Structured HTML table
- 🖥️ Displays 10 electronic products
- 💰 Shows quantity, unit price, and total amount for each product
- 🎨 Styled table using CSS
- 🖱️ Hover effect on table rows
- 📋 Highlighted table header
- ➕ Displays the grand total
- 📐 Centered table layout

Technologies Used

- HTML5
- CSS3

Project Structure

Electronics-Product-Table/
│
├── index.html
└── README.md

How to Run

1. Download or clone the project.
2. Open the project folder.
3. Open "index.html" in any modern web browser.
4. The Electronics Product Table will be displayed.

Table Columns

The table contains the following columns:

Column| Description
SR No.| Serial number of the product
Product Name| Name of the electronic product
Quantity| Number of units
Per Unit Price| Price of one unit
Amount| Total price for the given quantity

Products Included

The table contains the following products:

SR No.| Product| Quantity| Per Unit Price| Amount
1| Television| 48| ₹30,000| ₹14,40,000
2| Laptop| 24| ₹70,000| ₹16,80,000
3| Mobile| 25| ₹50,000| ₹12,50,000
4| Tablet| 23| ₹30,000| ₹6,90,000
5| PS5 Ultimate| 25| ₹70,000| ₹17,50,000
6| AC| 10| ₹60,000| ₹6,00,000
7| Sound System| 15| ₹10,000| ₹1,50,000
8| Dyson| 23| ₹50,000| ₹11,50,000
9| Fridge| 3| ₹3,00,000| ₹9,00,000
10| Inveter| 6| ₹40,000| ₹2,40,000

CSS Styling

Table

The table uses "border-collapse" to combine adjacent borders:

table {
    border-collapse: collapse;
    margin: auto;
    height: 100%;
    width: 80%;
    background-color: bisque;
}

Header

The table header is styled with a different background color:

th {
    background-color: darkseagreen;
}

Hover Effect

When the user moves the mouse over a table row, its background color changes:

tr:hover {
    background-color: aquamarine;
}

This makes the table more interactive and easier to read.

Total Amount

The table displays a grand total at the bottom:

<tr>
    <th colspan="4">Total</th>
    <th>9850000</th>
</tr>

«Note: The provided code calculates the total as "9,850,000". The individual row values should be checked if this table is intended for real billing or inventory use.»

Learning Objectives

This project helps beginners understand:

- Creating HTML tables
- Using "<table>", "<tr>", "<th>", and "<td>"
- Using "colspan"
- Applying CSS to HTML tables
- Using "border-collapse"
- Centering elements with "margin: auto"
- Creating hover effects with ":hover"
- Styling table headers and rows

Example Table Structure

<table border="1px">
    <tr>
        <th>SR No.</th>
        <th>Product Name</th>
        <th>Quantity</th>
        <th>Per Unit Price</th>
        <th>Amount</th>
    </tr>

    <tr>
        <td>1</td>
        <td>Television</td>
        <td>48</td>
        <td>30000</td>
        <td>1440000</td>
    </tr>
</table>

Future Improvements

The project could be improved by:

- Adding responsive table styling for mobile devices
- Using JavaScript to calculate amounts automatically
- Adding currency formatting
- Adding product images
- Adding search and filtering
- Using semantic HTML without deprecated attributes
- Adding a form to enter new products dynamically

Note

This is a frontend-only educational project. The product data is hard-coded in HTML, and the table does not currently calculate values dynamically.

License

This project is free to use for learning and personal projects.
