# Simple Calculator App – MATLAB App Designer

This is a basic calculator application built using **MATLAB App Designer**. It provides a graphical user interface for performing standard arithmetic operations such as **addition, subtraction, multiplication, division**, as well as **power** and **square root** calculations.

---

## 🧮 Features

- Input two numeric values
- Perform:
  - Addition
  - Subtraction
  - Multiplication
  - Division
  - Power (`Value1 ^ Value2`)
  - Square root (`sqrt(Value1)`)
- Display result in a read-only field
- Clear all input and output fields

---

## 🖥️ Interface Layout

- **Value 1 / Value 2**: Input fields for numbers
- **Answer**: Output field (non-editable)
- **Buttons**:
  - `Add`, `Subtract`, `Multiply`, `Divide`
  - `Square` (Value1 raised to Value2)
  - `Square Root` (of Value1 only)
  - `Clear`: Resets all fields to 0

---

## 🛠 How to Use

1. Open the app in **MATLAB App Designer** (`.mlapp` file).
2. Enter numeric values into `Value 1` and `Value 2` fields.
3. Click any operation button to compute the result.
4. View the result in the `Answer` field.
5. Use the `Clear` button to reset the fields.

---

## 📁 File Structure

- `SimpleCalculatorApp.mlapp`: Main App Designer file
- No additional scripts or dependencies required

---

## 🔧 Code Highlights

- Built as a MATLAB class extending `AppBase`
- UI components like `uibutton`, `uieditfield`, and `uilabel`
- Logical separation of UI setup (`createComponents`) and logic (`ButtonPushed` functions)
- Uses simple MATLAB operations and handles all math via callback functions

---

## 🧠 Requirements

- MATLAB R2018b or newer
- App Designer support enabled
- No additional toolboxes required

---

