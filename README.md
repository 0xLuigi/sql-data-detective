<img src="https://raw.githubusercontent.com/0xLuigi/sql-data-detective/main/images/sqlite.png" alt="SQLite Database Icon" style="width: 800px; height: 500px;">

If you are using the Firefox browser, MetaMask vault data can often be found in .sqlite database files 👆 <br>
You can open them with a standard text editor or by using a tool like [EmEditor](https://www.emeditor.com) or [Notepad++](https://notepad-plus-plus.org/)<br>

However, sometimes the MetaMask vault data might be incomplete, and you'll need to open the database and find this information in the **Object Data** table, specifically within the BLOB data field.

<p>
Therefore, I created this simple application 👇 that can find BLOB data and convert it into a readable format with a single click.
</p>

<img src="https://raw.githubusercontent.com/0xLuigi/sql-data-detective/main/images/blob.gif" alt="blob data">

## 🛠️ Installation & Usage

1. Open the file: Simply open the index.html file in any modern web browser (Chrome, Firefox, Edge).
2. Load the Database: Drag and drop your .sqlite file onto the upload area.

## 🚀 Technologies

- Core: HTML5, CSS3, JavaScript (ES6+)<br>
- Database Engine: SQL.js (A powerful port of SQLite to WebAssembly, enabling the entire database engine to run securely client-side in the browser.)<br>
- Security: 100% Client-Side / Offline. Your database file never leaves your computer.


## 💖 Support the Project

If this tool helped you fix your MetaMask wallet, consider supporting the development:

- **Bitcoin (BTC):** `bc1qgug43r48cceja46j9nmj686wps5vad8appytsh`
- **Ethereum (ETH):** `0x8A00f43C099bEB3F5d3C289e8b93c71c32B4d52e` 
