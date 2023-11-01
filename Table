<!DOCTYPE html>
<html>
<head>
    <title>Grid Input App</title>
    <style>
        table {
            border-collapse: collapse;
        }
        td {
            border: 1px solid black;
            padding: 5px;
        }
    </style>
</head>
<body>
    <h1>Grid Input App</h1>

    <table id="grid">
        <!-- Rows and Columns will be dynamically created using JavaScript -->
    </table>

    <script>
        // Define the number of rows and columns
        const rows = 4;
        const columns = 4;

        // Get the table element
        const grid = document.getElementById('grid');

        // Create rows and columns
        for (let i = 0; i < rows; i++) {
            const row = grid.insertRow();
            for (let j = 0; j < columns; j++) {
                const cell = row.insertCell();
                const input = document.createElement('input');
                input.setAttribute('type', 'text'); // Change to 'number' for numbers only
                input.setAttribute('class', 'grid-input');
                cell.appendChild(input);
            }
        </script>
    </body>
</html>
