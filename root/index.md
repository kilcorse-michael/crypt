<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://fonts.googleapis.com/css2?family=Special+Elite&display=swap" rel="stylesheet">
    <style>
        body{
            font-family: 'Special Elite', cursive;
            background-color: antiquewhite;
        }
        table, th, td {
            
            border: 1px solid black;
            border-collapse: collapse;
            }
        th, td {
            padding: 15px;
            }

        td{
            background-color: beige;
        }
        th{
            background-color: burlywood;
        }
    </style>
</head>
<body>
    <div>
        <center>
            <h1>Crack the CODE</h1>
        <table>
            <tr>
                <th class= "column"> </th>
                <th class= "column">A</th>
                <th class= "column">B</th>
                <th class= "column">C</th>
                <th class= "column">D</th>
                <th class= "column">E</th>
                <th class= "column">F</th>
                <th class= "column">G</th>
                <th class= "column">H</th>
            </tr>
            <tr>
                <th class = "row">A</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th class = "row">B</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th class = "row">C</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th class = "row">D</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th class = "row">E</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th class = "row">F</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr >
            <tr>
                <th class = "row">G</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th class = "row">H</th>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
        <h3>hint: ASCII</h3>
    </center>
    </div>
    <script type="text/javascript">
        const rows = document.querySelectorAll("td");
        const stringBin2= "0110001000101010011110100010101100101001001110100110000100100001"
        const stringArr = stringBin2.split('');

        for(let i = 0; i < rows.length; i++){
            for(let j = 0; j < 8; j++){
                rows[i].innerHTML = stringArr[i];
            }
        }
    </script>
</body>
</html>
