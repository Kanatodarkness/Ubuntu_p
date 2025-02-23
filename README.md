<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ubuntu - Sistemas Operativos</title>
    <style>
        :root {
            --primary-color: #b30000;
            --secondary-color: #ff4d4d;
            --background-color: #231e1e;
            --text-color: white;
            --table-bg: white;
            --table-border: #b30000;
        }
        body {
            font-family: 'Courier New', monospace;
            text-align: center;
            background-color: var(--background-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
        }
        .banner {
            font-size: 28px;
            color: var(--text-color);
            font-weight: bold;
            padding: 15px;
            background-color: var(--primary-color);
            text-transform: uppercase;
            letter-spacing: 2px;
            border-bottom: 4px solid var(--secondary-color);
            animation: pulse 3s infinite alternate;
        }
        @keyframes pulse {
            from { opacity: 0.8; }
            to { opacity: 1; }
        }
        table {
            width: 70%;
            margin: 20px auto;
            border-collapse: collapse;
            background: var(--table-bg);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 0 15px rgba(255, 77, 77, 0.5);
            color: black;
        }
        th, td {
            border: 2px solid var(--table-border);
            padding: 15px;
            font-size: 18px;
        }
        th {
            background-color: var(--primary-color);
            color: var(--text-color);
        }
        img {
            width: 200px;
            display: block;
            margin: 20px auto;
            border: 5px solid var(--text-color);
            border-radius: 10px;
            transition: transform 0.3s;
        }
        img:hover {
            transform: scale(1.1);
        }
        h1 {
            margin-top: 20px;
            color: var(--text-color);
            text-shadow: 2px 2px 4px rgba(255, 77, 77, 0.5);
        }
    </style>
</head>
<body>
    <div class="banner">Herramientas de Software y Sistemas Operativos</div>
    
    <h1>Lista de Versiones de Ubuntu</h1>
    <table>
        <tr>
            <th>Versión</th>
            <th>Año de Lanzamiento</th>
        </tr>
        <tr>
            <td>Ubuntu 20.04 LTS</td>
            <td>2020</td>
        </tr>
        <tr>
            <td>Ubuntu 22.04 LTS</td>
            <td>2022</td>
        </tr>
        <tr>
            <td>Ubuntu 23.10</td>
            <td>2023</td>
        </tr>
    </table>
    
    <img src="1.jpg" alt="Logo de Ubuntu"><img src="2.jpg" alt="Logo de Ubuntu"><img src="3.jpg" alt="Logo de Ubuntu">
</body>
</html>
