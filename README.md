# Product Table
## Date:
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href ="style.css" rel="stylesheet">
    <title>Document</title>
</head>
    <body>
        <h1>Product Table</h1>
        <table border="1" cellpadding="2">
            <thead>
                <tr>
                    <th>Product Name</th>
                    <th>Product Price</th>
                    <th>Description</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Laptop</td>
                    <td>$69,000</td>
                    <td>High-performance gaming laptop</td>
                </tr>
                <tr>
                    <td>Hand-bag</td>
                    <td>$50</td>
                    <td>Spacious and elegant</td>
                </tr>
                <tr>
                    <td>Bluetooth Airpods</td>
                    <td>$1,100</td>
                    <td>Excellent performance and high quality sound</td>
                </tr>
                <tr>
                    <td>Trimmer</td>
                    <td>$3,500</td>
                    <td>Long lasting battery and super sharp razor</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
```
## Live web page:
https://samjxdev.github.io/Product_Table/
## Output:
![image](https://github.com/user-attachments/assets/7790c5fb-47cc-4d27-b4ae-57aedc8bfa02)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
