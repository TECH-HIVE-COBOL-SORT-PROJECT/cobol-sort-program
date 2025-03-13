# 📌 COBOL Sorting Program

## 👨‍💻 Author
TECH HIVE

## 📅 Date
06 / 03 / 2025

## 🎯 Purpose
This COBOL program reads student names and grades from an input file (`📂 input.txt`), sorts the data based on grades in ascending order, and writes the sorted output to a new file (`📂 output.txt`).

## 🔧 Prerequisites
- 🖥 Open COBOL IDE
- ⚙️ COBOL Compiler (`cobc`)

## 📂 File Descriptions
- 📄 `input.txt`: Contains student names and grades.
- 📄 `output.txt`: Stores the sorted output.
- 📄 `SORTWORK`: Temporary storage used for sorting.

## 🚀 Compilation and Execution
1. Open the Open COBOL IDE.
2. Copy and paste the COBOL code into the editor.
3. Compile the program using:
   ```sh
   cobc -x program.cob
   ```
4. Ensure `input.txt` exists with student data before execution.
5. Run the compiled program:
   ```sh
   ./program
   ```

## ✅ Expected Output
- 📥 The program reads the data from `input.txt`.
- 🔀 It sorts students based on their grades.
- 📤 The sorted data is written to `output.txt`.
- 🎉 A success message **"PROGRAM EXECUTED SUCCESSFULLY"** is displayed.

## 📑 Example Input (`input.txt`)
```
Neo Malatsi          90
Neo Thobela          85
Nthabiseng Lekwano   78
Kgaugelo Mokgalaka   88
Xolani Mbambo        82
```

## 📑 Example Output (`output.txt`)
```
Nthabiseng Lekwano   78
Xolani Mbambo        82
Neo Thobela          85
Kgaugelo Mokgalaka   88
Neo Malatsi          90

```



