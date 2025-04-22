here's the code

    <!DOCTYPE html>
    <html lang="pt-BR">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LINKIN PARK WORLD TOUR</title>
    <style>
        body {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-color: darkred;
            margin: 20px;
            padding: 20px;
            text-align: center; 
        }

        h1{
            color: azure;
        }
        h2{
            color: azure;
        }

        .destaque {
            color: white;
            font-size: 18px;
            border: 2px dashed white;
            padding: 10px;
        }

        #especial {
            background-color: rgb(255, 255, 255);
            margin: 20px;
            padding: 15px;
            border: 2px solid black;
        }

    
        table {
            width: 80%; 
            margin: 0 auto; 
            border-collapse: collapse; 
            text-align: center; 
            border: 3px solid white; 
        }

        th, td {
            color: white; 
            padding: 10px;
            border: 2px solid white; 
        }

        form {
            margin-top: 20px;
        }

        label, input {
            display: block;
            margin: 10px auto;
            color: white;
        }

        button {
            background-color: black;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: white;
            color: black;
        }
    </style>
</head>
<body>
    <h1>LINKIN PARK:</h1>
    <h2>FROM ZERO WORLD TOUR</h2>

    <img src="linkin.jpg" alt="Um computador desktop" width="800">

    <video controls width="500" height="300">
        <source src="L2.mp4" type="video/mp4">
    </video>

    <audio controls>
        <source src="L3.mp3" type="audio/mp3">
    </audio>

    <h2>Schedules</h2>
    <table border="10">
        <thead>
            <tr>
                <th>MAI.8</th>
                <th>MAI.10</th>
                <th>MAI.17</th>
                <th>MAI.20</th>
                <th>MAI.27</th>
                <th>MAI.31</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>19:30</td>
                <td>15:00</td>
                <td>18:00</td>
                <td>15:00</td>
                <td>18:00</td>
                <td>19:00</td>
            </tr>
        </tbody>
    </table>

    <h2>Forms</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name">

        <label for="e-mail">E-mail:</label>
        <input type="email" id="e-mail">

        <label for="telefone">Phone Number:</label>
        <input type="tel" id="telefone" name="telefone">

        <label>
            <input type="checkbox" name="notificacao" value="e-mail">
            Receber atualizações por e-mail
        </label>

        <button type="submit">Enviar formulário</button>
    </form>
</body>
</html>
