<!DOCTYPE html>
<html lang="en">
<body>
    <div style="font-family: Arial, sans-serif; background-color: #f0f0f0; margin: 0; padding: 0;">
        <div style="max-width: 800px; margin: 0 auto; padding: 20px; background-color: #fff; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); border-radius: 10px;">
            <h1 style="color: #1fa0ff; text-align: center;">Personal Banking Website</h1>
            <p>This platform provides a user friendly interface for you to effortlessly handle your personal banking. You have the flexibility to carry out multiple tasks, like depositing funds, making withdrawals and checking your account balance.</p>
            <h2>How to Use the Website</h2>
            <ul style="list-style: none; padding: 0;">
                <li style="margin-bottom: 10px;">Access the Website: Open the provided HTML file, <code>index.html</code>, in a web browser.</li>
                <li style="margin-bottom: 10px;">Homepage: You'll see a webpage titled "Financial Account Administration" with a background image and a heading that says "Welcome to Your Personal Banking Account."</li>
                <li style="margin-bottom: 10px;">Buttons: There are three buttons:</li>
                <ul style="list-style: none; padding: 0;">
                    <li style="margin-bottom: 10px;"><strong>Deposit:</strong> Click this button to deposit money into your account. You will be prompted to enter the deposit amount. If the input is valid (a positive number), the deposit will be made, and a success message will appear. If there's an error (e.g., negative input or invalid characters), an error message will be displayed.</li>
                    <li style="margin-bottom: 10px;"><strong>Withdraw:</strong> Click this button to withdraw money from your account. You'll be prompted to enter the withdrawal amount. Similar to the deposit, it will validate the input and either perform the withdrawal or show an error message.</li>
                    <li style="margin-bottom: 10px;"><strong>Check Balance:</strong> Click this button to check your current account balance. It will display your balance.</li>
                </ul>
            </ul>
            <h2>Walkthrough of Code</h2>
            <p>The JavaScript code of this website incorporates the use of classes, switch statements, and try-catch-finally statements:</p>
            <ul style="list-style: none; padding: 0;">
                <li style="margin-bottom: 10px;"><strong>Classes:</strong> The <code>BankAccount</code> class is used to represent a bank account. It has methods for depositing, withdrawing, and checking the balance.</li>
                <li style="margin-bottom: 10px;"><strong>Switch Statements:</strong> A switch statement is used to determine the action based on the button clicked by the user ("Deposit," "Withdraw," or "Check Balance").</li>
                <li style="margin-bottom: 10px;"><strong>Try-Catch-Finally Statements:</strong> Try-catch blocks handle exceptions when the user enters invalid input or attempts to withdraw more than the account balance. Error messages are displayed using the <code>showAlert</code> function.</li>
            </ul>
        </div>
    </div>
</body>
</html>
