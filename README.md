## SQL Data 🕵️‍♂️ Detective

<img src="https://raw.githubusercontent.com/0xLuigi/sql-data-detective/main/images/sqlite.png" alt="SQLite Database Icon" style="width: 800px; height: 500px;">

If you are using the Firefox browser, MetaMask vault data can often be found in .sqlite database files 👆 <br>
You can open them with a standard text editor or by using a tool like [EmEditor](https://www.emeditor.com) or [Notepad++](https://notepad-plus-plus.org/)<br>

However, sometimes the MetaMask vault data might be incomplete, and you'll need to open the database and find this information in the **Object Data** table, specifically within the BLOB data field.

<p>
Therefore, I created this simple application 👇 that can find BLOB data and convert it into a readable format with a single click.
</p>

<img src="https://raw.githubusercontent.com/0xLuigi/sql-data-detective/main/images/blob.gif" alt="blob data">

## 🛠️ Installation & Usage

1. Download here: https://github.com/0xLuigi/sql-data-detective/archive/refs/heads/main.zip
2. Unzip the downloaded archive.
3. Open the file: Simply open the index.html file in any modern web browser (Chrome, Firefox, Edge).
4. Load the Database: Drag and drop your .sqlite file onto the upload area.

## 🚀 Technologies

- Core: HTML5, CSS3, JavaScript (ES6+)<br>
- Database Engine: SQL.js (A powerful port of SQLite to WebAssembly, enabling the entire database engine to run securely client-side in the browser.)<br>
- Security: 100% Client-Side / Offline. Your database file never leaves your computer.

## 🚀 Key Features

- Offline Functionality: Runs completely in the browser using SQL.js (WebAssembly), ensuring data privacy. Your file never leaves your computer.
- Advanced Search: Search for keywords across all data, including a sophisticated attempt to decode and search within BLOB fields.
- BLOB Viewer: Dedicated viewer for binary data, supporting Hex view, UTF-8 text conversion, copying, and downloading the raw .bin file.
- i18n Support: Available in Slovak, English, Italian, and German.
- UX: Dark/Light mode toggle and saved query management.

## 💖 Support the Project

If this tool helped you fix your MetaMask wallet, consider supporting the development:

- **Bitcoin (BTC):** `bc1qgug43r48cceja46j9nmj686wps5vad8appytsh`
- **Ethereum (ETH):** `0x8A00f43C099bEB3F5d3C289e8b93c71c32B4d52e` 
