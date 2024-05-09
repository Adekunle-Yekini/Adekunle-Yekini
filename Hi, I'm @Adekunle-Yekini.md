<!DOCTYPE html>
<html>
<head>
    <title>Money Transfer App</title>
    <script type="text/javascript">
        function transferMoney() {
            var fromAccount = prompt("Enter your account number:");
            var toAccount = prompt("Enter the recipient's account number:");
            var amount = prompt("Enter the amount to transfer:");

            if (confirm("Transfer $" + amount + " from account " + fromAccount + " to account " + toAccount + "?")) {
                alert("Transfer successful!");
            } else {
                alert("Transfer cancelled.");
            }
        }
    </script>
</head>
<body>
    <h1>Welcome to the Money Transfer App</h1>
    <button onclick="transferMoney()">Transfer Money</button>
</body>
</html>