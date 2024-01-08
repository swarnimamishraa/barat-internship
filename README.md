# barat-internship
<title>MONEY TRACKER WEBAPP</title>
</head>
<body>
    <h1> Money Tracker Web App</h1>
    <div class="input-section">
        <label for="category-select">category:</label>
        <select id="category-select">
            <option value="college fee">College Fee</option>
            <option value="Rent">Rent</option>
            <option value="Transport">Transport</option>
            <option value="Food">Food</option>
            <option value="Shopping">Shopping</option>
            <option value="Cool Drinks">Cool Drinks</option>
        </select>
        <label for="amount-input">Amount:</label>
        <input type="number" id="amount-input">
        <label for="date-input">Date:</label>
        <input type="date" id="date-input">
        <button id="add-btn">Add</button>
    </div>
    <div class="expenses-list">
        <h2>Expenses-List</h2>
        <table>
            <Thread>
                <tr>
                    <th>Category</th>
                    <th>Amount</th>
                    <th>Date</th>
                    <th>Delete</th>
                </tr>
            </Thread>
            <tbody id="expenses-table-body">

            </tbody>
            <tfoot>
                <td>Total:</td>
                <td id="total-amount"></td>
                <td></td>
                <td></td>
            </tfoot>
        </table>
    </div>
    <script src="script.js"></script>
</body>
</html>
