<img src="https://raw.githubusercontent.com/0xLuigi/sql-data-detective/main/images/sqlite.png" alt="SQLite Database Icon" style="width: 800px; height: 500px;">

If you are using the Firefox browser, MetaMask vault data can often be found in .sqlite database files 👆 <br>
You can open them with a standard text editor or by using a tool like [EmEditor](https://www.emeditor.com) or [Notepad++](https://notepad-plus-plus.org/)<br>

However, sometimes the MetaMask vault data might be incomplete, and you'll need to open the database and find this information in the **Object Data** table, specifically within the BLOB data field.

<p>
Therefore, I created this simple application 👇 that can find BLOB data and convert it into a readable format with a single click.
</p>

<img src="https://raw.githubusercontent.com/0xLuigi/sql-data-detective/main/images/blob.gif" alt="blob data">
