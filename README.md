 <!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <title>Online store-Product Listing</title>
        <style>
            body {
              font-family: Arial,sans-serif;
              margin: 0;
              padding: 20px;
              background: color #f4f4f4;
            }
            h1 {
                text-align: center;
                color: #333;
            }
            table {
                width:100%;
                border-collapse: collapse;
                margin:20px 0;
                background-color:#fff;
            }
            th,td {
                padding: 15px;
                text-align: left;
                border: 1px solid #ddd;
            }
            th {
                background-color: #f2f2f2;
            }
            tr:nth-child(even){
                background-color: #f9f9f9;
            }
            tr:hover{
                background-color:#f1f1f1;
            }
            img {
                width: 100px;
                height:auto;
            }
            purchase-link{
                text-decoration:none;
                color:white;
                background-color:#4CAF50;
                padding:10px 20px;
                border-radius:5px;
            }
            purchase-link:hover{
                background-color: #45a049;
            }
        </style>
    </head>
<body>
    <h1>Product listing</h1>
    <table>
        <thead>
            <tr>
                <th>image</th>
                <th>Product Name</th>
                <th>Description</th>
                <th>Price</th>
                <th>Buy Now</th>
            </tr>
        </thead>
    </table>
</body>
<body>
<table>
<tr>
    <td><img src="https://th.bing.com/th?id=OIP.1h-JoBXyXUBffhvK3Q_tGwHaGQ&w=272&h=229&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=3.1&rm=2"alt="buy-product1"></td>
    <td>I phone 7</td>
    <td>The i phone 7 comes in black,silver and gold.It has storage options of 32GB,128GB and 256GB.</td>
    <td>ksh.35,000</td>
    <td><a href="buy-product1.html"
    class="Product-link">Buy Now</a></td>
</tr>
<tr>
    <td><img src="https://www.bing.com/th?id=OIP.bQ3GXoIgs905LMUQbJfRkgAAAA&w=306&h=203&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=3.1&rm=2"alt="Product 2"></td>
    <td>I phone 12</td>
    <td>The I phone 12 comes in blue,green and red.It has storage options of 64GB,128GB and 256GB.</td>
    <td>ksh.65,000</td>
    <td><a href="buy product2.html."class="purchase-link">Buy Now</a></td>
    </tr>
    <tr>
        <td><img src="https://www.bing.com/th?id=OIP.SrW_WbDqz8R-ydbVTOVIQAAAAA&w=250&h=250&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=3.1&rm=2"alt="Product 3"></td>
        <td>I phone 13</td>
        <td>The I phone 13 comes with Pink,Blue and Black.It has storage options of 128GB,256GB and 512GB.</td>
        <td>ksh.85,000</td>
        <td><a href="buy-product3.html"class="purchase-link">Buy Now</a></td>
    </tr>
</tbody>
</table>
</html>
