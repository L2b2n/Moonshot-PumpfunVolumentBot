Instructions for Running the solana-bo-pump-win.exe
1. Download and Extract the Files
Download the solana-bo-pump-win.exe file from the provided source.
Extract the file if it is inside a compressed folder.
2. Run the .exe File
Double-click the solana-bo-pump-win.exe file to start the application.
If you see a warning message from Windows, such as "Windows protected your PC", click on "More info" and then "Run anyway".
3. Enter Required Information
The application will prompt you to enter several pieces of information. Here’s what you’ll need:

RPC URL: The URL of the Solana RPC server you are using. You can find this from your Solana provider or the project you are working with.
Wallet Private Key: The private key of your Solana wallet, encoded in Base58 format. This key should be kept secret and secure.
Amount of SOL: The amount of SOL you want to use for purchasing tokens.
Amount of Tokens to Purchase: The number of tokens you wish to buy, without including decimal places.
Number of Buys Before Selling: The number of purchases you want to make before executing a sell.
Token Mint Address: The public address of the token you want to buy. This is a Solana address you can find on Solscan or from the token provider.
Bonding Curve Account Address: The address of the bonding curve account for the token you are buying.
Associated Bonding Curve Account Address: The associated bonding curve account address, often provided by the token issuer or found in the contract details.
4. Copying Data from Solscan
To find the Token Mint Address, Bonding Curve Account Address, and other necessary addresses:
Visit Solscan: Go to Solscan.
Search the Token: Enter the token name or contract address in the search bar.
Copy Addresses: Navigate to the "Token" tab and find the Mint Address. For Bonding Curve Account and Associated Bonding Curve Account, you may need to check the token's smart contract details or consult the project documentation.
5. Execution and Monitoring
After entering all the required information, the bot will begin executing buy and sell orders based on your inputs.
You will see logs in the console providing updates on each transaction.
6. Checking Transactions
To check the transactions executed by the bot:
Copy Transaction IDs from Console: The bot will display transaction IDs after each buy/sell.
Search on Solscan: Paste the transaction ID into Solscan to view the details of each transaction.
7. Stopping the Bot
To stop the bot, simply close the console window or terminate the process through Task Manager.
8. Security Considerations
Always keep your private key secure. Never share it with anyone.
Use the bot only in a secure environment where your private key cannot be intercepted.
If you encounter any issues or need further assistance, feel free to reach out to the support team or check the documentation related to the bot.
