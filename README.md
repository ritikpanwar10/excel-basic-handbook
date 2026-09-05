<div align="center">

# 📊 Excel Basic Handbook

A structured reference guide and practice repository covering essential Excel fundamentals, interface navigation, workbook security, and basic arithmetic operations.

[![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Status](https://img.shields.io/badge/Documentation-Complete-brightgreen?style=for-the-badge)](#)

<br/>

<img width="650" alt="Excel Overview" src="https://github.com/user-attachments/assets/389ada31-24ea-4372-ad78-2946b45c64fa" />

</div>

---

## 📑 Table of Contents
1. [Worksheet Limits & Structure](#-worksheet-limits--structure)
2. [Key Interface Components](#%EF%B8%8F-key-interface-components)
3. [Cell & Row Adjustments](#%EF%B8%8F-cell--row-adjustments)
4. [Managing Rows & Columns](#%EF%B8%8F-managing-rows--columns)
5. [Visibility: Hide & Unhide](#%EF%B8%8F-visibility-hide--unhide)
6. [Essential Keyboard Shortcuts](#%EF%B8%8F-essential-keyboard-shortcuts)
7. [Workbook Security: Password Encryption](#-workbook-security-password-encryption)
8. [Basic Arithmetic Operators](#-basic-arithmetic-operators)
9. [Basic Addition Formula](#-basic-addition-formula)
10. [Calculating Totals with AutoFill](#-calculating-totals-with-autofill)

---

## 📐 Worksheet Limits & Structure

| Metric | Specification | Details |
| :--- | :---: | :--- |
| **Total Columns** | `16,384` | Labeled from `A` through `XFD` |
| **Total Rows** | `1,048,576` | Numbered from `1` through `1,048,576` |
| **Total Cells** | `~17.18 Billion` | Exact: 1,048,576 × 16,384 |

---

## 🖥️ Key Interface Components

<div align="center">
  <img width="640" alt="Key Components" src="https://github.com/user-attachments/assets/e2485c3e-09dc-4cef-b3cd-8100d4c1adc0" />
</div>

* **Ribbon & Tabs:** The primary control toolbar housing all tools and commands (`Home`, `Insert`, `Formulas`, `Data`, etc.).
* **Name Box:** Displays the address/reference of the active selection (e.g., `C5`).
* **Formula Bar (`fx`):** Displays and allows direct editing of values, labels, or underlying formulas in the active cell.
* **Active Cell:** The currently selected cell, indicated by a bold green border.
* **Status Bar:** Bottom horizontal strip displaying quick calculations (**Average**, **Count**, **Sum**) for highlighted ranges.

---

## 🛠️ Cell & Row Adjustments

### Adjust Row Height
Resize rows manually by dragging the boundary line between row numbers, or specify exact measurements using the ribbon format options.

<div align="center">
  <img width="70%" alt="Adjust Row Height" src="https://github.com/user-attachments/assets/3824f3b2-1bda-4e64-a186-e550408a424c" />
</div>

---

## ✂️ Managing Rows & Columns

### How to Delete an Entire Row

<div align="center">
  <img height="190" alt="Step 1 - Select Row" src="https://github.com/user-attachments/assets/fd18c37a-06c0-4e6e-8f4a-2095ea704e97" />
  &nbsp;&nbsp;
  <img height="190" alt="Step 2 - Right Click Menu" src="https://github.com/user-attachments/assets/f9da2262-0c83-4c79-aa29-2ef83e867681" />
  &nbsp;&nbsp;
  <img height="190" alt="Step 3 - Row Deleted" src="https://github.com/user-attachments/assets/a3688bc4-eb51-4e21-8dda-29f3384b1c1d" />
</div>

> [!TIP]
> * **Clear Contents vs. Delete:** If you want to erase cell data without removing the physical row structure, right-click and select **Clear Contents** (or press the `Delete` key).
> * **Columns:** The identical method applies to columns by right-clicking on the respective column header.

---

## 👁️ Visibility: Hide & Unhide

### 1. Columns & Rows

<table>
  <tr>
    <th width="40%">Visual Action</th>
    <th width="60%">Instructions</th>
  </tr>
  <tr>
    <td align="center">
      <img width="220" alt="Hide Column Menu" src="https://github.com/user-attachments/assets/415129b1-b441-4194-affe-578a4a0d554d" />
    </td>
    <td>
      <h4>How to Hide:</h4>
      <ol>
        <li>Right-click the <b>Header</b> of the column you want to hide (e.g., <code>B</code>).</li>
        <li>Select <b>Hide</b> from the context menu.</li>
        <li>A double-divider line will appear in place of the hidden column.</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img width="220" alt="Unhide Column" src="https://github.com/user-attachments/assets/15442424-40f7-42b1-9562-64fe5b50c69d" />
    </td>
    <td>
      <h4>How to Unhide:</h4>
      <ul>
        <li>Highlight the columns adjacent to both sides of the hidden column (e.g., <code>A</code> and <code>C</code>).</li>
        <li>Right-click the selection and choose <b>Unhide</b>.</li>
        <li><i>Alternative:</i> Hover over the double-divider line until the resize pointer appears, then drag outward.</li>
      </ul>
    </td>
  </tr>
</table>

### 2. Worksheets

<table>
  <tr>
    <td width="40%" align="center">
      <img width="240" alt="Hide Sheet Menu" src="https://github.com/user-attachments/assets/7f843888-0889-4127-abf6-3905c11d34be" />
    </td>
    <td width="60%">
      <h4>Hide a Worksheet</h4>
      <ol>
        <li>Right-click the target <b>Sheet Tab</b> (e.g., <code>Sheet2</code>) at the bottom.</li>
        <li>Select <b>Hide</b>.</li>
      </ol>
      <hr />
      <h4>Unhide a Worksheet</h4>
      <ol>
        <li>Right-click on any visible sheet tab.</li>
        <li>Select <b>Unhide...</b> from the menu.</li>
        <li>Choose the worksheet name from the prompt dialog and click <b>OK</b>.</li>
      </ol>
    </td>
  </tr>
</table>

---

## ⌨️ Essential Keyboard Shortcuts

| Task | Windows Shortcut | Mac Shortcut |
| :--- | :---: | :---: |
| **Hide Selected Column** | `Ctrl + 0` | `Ctrl + 0` |
| **Hide Selected Row** | `Ctrl + 9` | `Ctrl + 9` |
| **Unhide Rows** | `Ctrl + Shift + 9` | `Ctrl + Shift + 9` |
| **Unhide Columns** | `Ctrl + Shift + 0` | `Ctrl + Shift + 0` |
| **Copy Selection** | `Ctrl + C` | `Cmd + C` |
| **Cut Selection** | `Ctrl + X` | `Cmd + X` |
| **Paste Standard** | `Ctrl + V` | `Cmd + V` |
| **Paste Special Dialog** | `Ctrl + Alt + V` | `Cmd + Ctrl + V` |
| **Paste Values Only** | `Ctrl + Shift + V` | `Cmd + Shift + V` |

---

## 🔒 Workbook Security: Password Encryption

Encrypting an Excel file applies standard AES encryption to the document. Once encrypted, unauthorized users without the password cannot decrypt, inspect, or modify the contents.

### Step 1: Open Info and Select 'Encrypt with Password'
1. Click the **File** tab in the top-left corner of the ribbon.
2. Navigate to **Info** in the left sidebar.
3. Click **Protect Workbook** and select **Encrypt with Password**.

<div align="center">
  <img width="520" alt="Protect Workbook Menu" src="https://github.com/user-attachments/assets/c65aa380-d7af-444e-8699-2abc48640176" />
</div>

---

### Step 2: Set and Confirm Password
1. Enter your designated password in the input field and click **OK**.
2. Re-enter the exact same password in the confirmation prompt and click **OK**.

<div align="center">
  <img width="380" alt="Encrypt Password Dialog" src="https://github.com/user-attachments/assets/5e2a111e-4334-4abe-987a-a255e70c42f7" />
</div>

> [!CAUTION]
> * Passwords are **case-sensitive**.
> * Microsoft Excel does not provide password recovery options. Store passwords securely in an encrypted password manager.

---

### Step 3: Save the Encrypted Workbook
Save the file by pressing `Ctrl + S` or navigating to **File** > **Save As** (`F12`). Encryption settings only take full effect after the file is saved to storage.

<div align="center">
  <img width="700" alt="Save As Dialog" src="https://github.com/user-attachments/assets/a691c37d-816d-4aa8-ba18-22a4437573e1" />
</div>

---

### Step 4: Verify Password Protection
Close Microsoft Excel and reopen the file. Excel will immediately display a verification prompt requiring authentication before rendering any sheet data:

<div align="center">
  <img width="650" alt="Password Prompt Verification" src="https://github.com/user-attachments/assets/c9e0e93b-aa6c-4575-a732-97aca8b965d0" />
</div>

> [!NOTE]
> **How to Remove Password Protection:** Open the file with your current password, head to **File** > **Info** > **Protect Workbook** > **Encrypt with Password**, clear the password field completely, click **OK**, and save the workbook.

---

## ➕ Basic Arithmetic Operators

| Operator | Operation | Example Formula | Output Description |
| :---: | :--- | :---: | :--- |
| `+` | **Addition** | `=A2 + B2` | Adds the values of cells A2 and B2 |
| `-` | **Subtraction** | `=A2 - B2` | Subtracts B2 from A2 |
| `*` | **Multiplication** | `=A2 * B2` | Multiplies A2 by B2 |
| `/` | **Division** | `=A2 / B2` | Divides A2 by B2 |
| `^` | **Exponentiation** | `=A2 ^ B2` | Raises A2 to the power of B2 |
| `%` | **Percentage** | `=A2 * 10%` | Computes 10% of cell A2 |

---

## 🧮 Basic Addition Formula

### Sample Dataset

| Name | Maths (Column B) | Science (Column C) | Total (Column D) |
| :--- | :---: | :---: | :---: |
| **A** | 60 | 79 | *(Formula)* |
| **B** | 59 | 69 | *(Formula)* |
| **C** | 54 | 59 | *(Formula)* |

---

### Step 1: Start with an Equals Sign (`=`)
Click on the target destination cell **D2** and type `=`. Every Excel calculation or formula requires an equals sign prefix to initiate computation.

<div align="center">
  <img width="380" alt="Formula Start with Equals" src="https://github.com/user-attachments/assets/1c640328-3b77-4fca-8918-4e0dc0ead5a6" />
</div>

---

### Step 2: Reference Target Cells
Click cell **B2**, enter the addition operator `+`, and then click cell **C2**. The assembled formula in **D2** will be `=B2+C2`. Press **Enter** to evaluate.

<div align="center">
  <img width="350" alt="Adding Cell References" src="https://github.com/user-attachments/assets/20852f2e-76d8-4cec-a97b-4a9754669eeb" />
</div>

---

### Step 3: Working via the Formula Bar (`fx`)
Formulas can also be typed, reviewed, and audited directly within the **Formula Bar** located above the worksheet grid:

<div align="center">
  <img width="420" alt="Formula Bar Edit" src="https://github.com/user-attachments/assets/c598df81-db4c-4f32-9613-a14f7162ab81" />
</div>

---

## ⚡ Calculating Totals with AutoFill

Excel's **AutoFill** tool automatically propagates relative formulas across continuous ranges, eliminating manual formula entry for every row.

### Step 1: Target the Fill Handle
Move the cursor to the bottom-right corner of the active cell (e.g., `D3`) until the pointer transforms into a solid black plus sign (`+`).

<div align="center">
  <img width="460" alt="Hover Fill Handle" src="https://github.com/user-attachments/assets/cd028395-747e-4c04-a8ce-490d28741294" />
</div>

---

### Step 2: Drag to AutoFill
Click and drag the handle down through cell **D5** (or double-click the handle) to apply the calculation to all adjacent rows.

<div align="center">
  <img width="460" alt="Drag Down to AutoFill" src="https://github.com/user-attachments/assets/eba6263b-bd0e-4e89-a23d-961a58a27c90" />
</div>
