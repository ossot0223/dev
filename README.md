<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primera web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
            text-align: center;
            margin-bottom: 20px;
        }
        p {
            color: #666;
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            padding: 10px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: #f2f2f2;
            color: #333;
        }
        img {
            max-width: 100px;
            height: auto;
            display: block;
            margin: 0 auto;
        }
        hr {
            border: none;
            height: 1px;
            background-color: #ddd;
            margin: 20px 0;
        }
        .button {
            display: block;
            width: 100px;
            margin: 0 auto;
            padding: 10px;
            text-align: center;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
        .button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>CERTUS CLASE 2</h1>
        <h2>LABORATORIO 3</h2>
        <p>OSCAR SOTELO</p>
        <hr>
        <h1>OFERTAS</h1>
        <table>
            <tr>
                <th>Código</th>
                <th>Producto</th>
                <th>Precio</th>
                <th>Imagen</th>
            </tr>
            <tr>
                <td>001</td>
                <td>Televisor</td>
                <td>1500 soles</td>
                <td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS441HsMyz-0yZdzJx3lqC4O81OZaJzzqqzphA8HKLoTA&s" alt="Televisor"></td>
            </tr>
            <tr>
                <td>002</td>
                <td>Microondas</td>
                <td>650 soles</td>
                <td><img src="https://www.lg.com/content/dam/channel/wcms/pe/images/microondas/mh7032jas_bbkglpr_espr_pe_c/Basic-450.jpg" alt="Microondas"></td>
            </tr>
            <tr>
                <td>003</td>
                <td>Refrigerador</td>
                <td>1000 soles</td>
                <td><img src="https://cdn11.bigcommerce.com/s-dj46qhetxl/images/stencil/1280x1280/products/137849/386895/irdrotqaqdqdnbj7lqkq__78811.1692328643.jpg?c=1" alt="Refrigerador"></td>
            </tr>
        </table>
        <a href="#" class="button">Ver más</a>
    </div>
</body>
</html>
