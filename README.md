# 📊 Excel Basic & Mathematical Formulas Handbook

> A structured reference guide and practice repository covering essential Excel fundamentals, interface navigation, and basic arithmetic functions.

Microsoft Excel is a spreadsheet program in the Microsoft 365 (Office) suite. It organizes data into a structured grid of rows and columns to store, calculate, analyze, and visualize numeric and textual records.

<p align="center">
  <img width="560" alt="Excel Overview" src="https://github.com/user-attachments/assets/389ada31-24ea-4372-ad78-2946b45c64fa" />
</p>

---

## 📐 Worksheet Limits & Structure

| Metric | Specification | Details |
| :--- | :--- | :--- |
| **Total Columns** | `16,384` | Labeled from `A` through `XFD` |
| **Total Rows** | `1,048,576` | Numbered `1` through `1,048,576` |
| **Total Cells** | `~17.18 Billion` | Exact: $1,048,576 \times 16,384$ |

---

## 🖥️ Key Interface Components

<p align="center">
  <img width="640" alt="Key Components" src="https://github.com/user-attachments/assets/e2485c3e-09dc-4cef-b3cd-8100d4c1adc0" />
</p>

* **Ribbon & Tabs:** The primary control toolbar housing all tools and commands (`Home`, `Insert`, `Formulas`, `Data`, etc.).
* **Name Box:** Displays the address/reference of the active selection (e.g., `C5`).
* **Formula Bar (`fx`):** Displays and allows editing of values, text, or underlying formulas in the selected cell.
* **Active Cell:** The currently selected cell, indicated by a thick outline.
* **Status Bar:** Bottom horizontal strip displaying quick calculations (**Average**, **Count**, **Sum**) for selected data.

---

## 🛠️ Cell & Row Adjustments

### Adjust Row Height
Resize rows manually by dragging row borders or via the ribbon format menu.

<p align="center">
  <img width="80%" alt="Adjust Row Height" src="https://github.com/user-attachments/assets/3824f3b2-1bda-4e64-a186-e550408a424c" />
</p>

---

## ✂️ Managing Rows & Columns

### How to Delete an Entire Row
Follow these visual steps to remove row entries:

<p align="center">
  <img height="210" alt="Step 1 - Select Row" src="https://github.com/user-attachments/assets/fd18c37a-06c0-4e6e-8f4a-2095ea704e97" />
  &nbsp;&nbsp;
  <img height="210" alt="Step 2 - Right Click Menu" src="https://github.com/user-attachments/assets/f9da2262-0c83-4c79-aa29-2ef83e867681" />
  &nbsp;&nbsp;
  <img height="210" alt="Step 3 - Row Deleted" src="https://github.com/user-attachments/assets/a3688bc4-eb51-4e21-8dda-29f3384b1c1d" />
</p>

> [!TIP]
> * **Clear Contents vs. Delete:** Agar poori row delete nahi karni, sirf data hatana hai, toh right-click karke **Clear Contents** (ya `Delete` key) press karein.
> * **Columns:** Yahi exact method column header par right-click karke columns ke liye bhi use hota hai.

---

## 👁️ Visibility: Hide & Unhide

### 1. Columns & Rows

<table>
  <tr>
    <td width="40%" align="center">
      <img width="220" alt="Hide Column Menu" src="https://github.com/user-attachments/assets/415129b1-b441-4194-affe-578a4a0d554d" />
    </td>
    <td width="60%" valign="middle">
      <h4>How to Hide:</h4>
      <ol>
        <li>Jis column ko hide karna hai uske <b>Header</b> (jaise <code>B</code>) par right-click karein.</li>
        <li>Menu se <b>Hide</b> select karein.</li>
        <li>Hidden column ki jagah double-divider line show hogi.</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td width="40%" align="center">
      <img width="220" alt="Unhide Column" src="https://github.com/user-attachments/assets/15442424-40f7-42b1-9562-64fe5b50c69d" />
    </td>
    <td width="60%" valign="middle">
      <h4>How to Unhide:</h4>
      <ul>
        <li>Hidden column ke aage aur peeche wale columns select karein (e.g., <code>A</code> aur <code>C</code>).</li>
        <li>Right-click karke <b>Unhide</b> choose karein.</li>
        <li><i>Alternative:</i> Double-divider line par mouse cursor le jaakar right-side drag karein.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 2. Worksheets

<table>
  <tr>
    <td width="40%" align="center">
      <img width="240" alt="Hide Sheet Menu" src="https://github.com/user-attachments/assets/7f843888-0889-4127-abf6-3905c11d34be" />
    </td>
    <td width="60%" valign="middle">
      <h4>Hide a Worksheet</h4>
      <ol>
        <li>Neeche <b>Sheet Tab</b> (e.g., <code>Sheet2</code>) par right-click karein.</li>
        <li><b>Hide</b> select karein.</li>
      </ol>
      <hr />
      <h4>Unhide a Worksheet</h4>
      <ol>
        <li>Kisi bhi active sheet tab par right-click karein.</li>
        <li><b>Unhide...</b> par click karein.</li>
        <li>Dialog box me se sheet name select karke <b>OK</b> karein.</li>
      </ol>
    </td>
  </tr>
</table>

---

## ⌨️ Essential Keyboard Shortcuts

| Task | Windows Shortcut | Mac Shortcut |
| :--- | :--- | :--- |
| **Hide Selected Column** | `Ctrl + 0` | `Ctrl + 0` |
| **Hide Selected Row** | `Ctrl + 9` | `Ctrl + 9` |
| **Unhide Rows** | `Ctrl + Shift + 9` | `Ctrl + Shift + 9` |
| **Unhide Columns** | `Ctrl + Shift + 0` | `Ctrl + Shift + 0` |
| **Copy** | `Ctrl + C` | `Cmd + C` |
| **Cut** | `Ctrl + X` | `Cmd + X` |
| **Paste** | `Ctrl + V` | `Cmd + V` |
| **Paste Special Dialog** | `Ctrl + Alt + V` | `Cmd + Ctrl + V` |
| **Paste Values Only** | `Ctrl + Shift + V` | `Cmd + Shift + V` |

---

## ➕ Basic Arithmetic Operators

| Operator | Operation | Example Formula | Output Description |
| :---: | :--- | :--- | :--- |
| `+` | **Addition** | `=A2 + B2` | Adds value of A2 and B2 |
| `-` | **Subtraction** | `=A2 - B2` | Subtracts B2 from A2 |
| `*` | **Multiplication** | `=A2 * B2` | Multiplies A2 by B2 |
| `/` | **Division** | `=A2 / B2` | Divides A2 by B2 |
| `^` | **Exponentiation** | `=A2 ^ B2` | Raises A2 to the power of B2 |
| `%` | **Percentage** | `=A2 * 10%` | Calculates 10% of A2 |
