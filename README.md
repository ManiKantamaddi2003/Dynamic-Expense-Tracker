# 📊 Dynamic Expense Tracker
![Screenshot 2025-02-16 105619](https://github.com/user-attachments/assets/fea572d1-4da8-406d-9af3-42c171abbf54)

## 📝 Overview

The **Dynamic Expense Tracker** is a simple web application designed to help users manage their finances by tracking income and expenses. Users can add transactions, view totals for income and expenses, and see their remaining balance dynamically updated.

## 🚀 Features

- ➕ Add transactions with date, amount, and type (income/expense)
- 📊 Display total income, total expense, and balance
- ❌ Remove transactions dynamically
- 📱 Responsive design using Bootstrap

## 🛠️ Technologies Used

- 🏗️ **HTML**: Structure of the webpage
- 🎨 **CSS (Bootstrap)**: Styling and responsive design
- 🔢 **JavaScript**: Dynamic interaction and calculations

## ⚙️ Installation & Usage

1. 📥 Clone or download the repository.
2. 🌐 Open `index.html` in a web browser.
3. 🎯 Start adding transactions and track your expenses in real time.

## 📂 Project Structure

```
/ (Root Directory)
|-- index.html  # Main HTML file
|-- style.css   # Optional custom styling (if added)
|-- script.js   # JavaScript for interactivity (included in HTML)
|-- images/     # Contains all necessary images/icons
```

## ♿ Accessibility Fix

To resolve the accessibility issue reported by **Microsoft Edge Tools (axe/forms)**:

- Add a label for the `select` element:
  ```html
  <label for="transaction-type">Transaction Type</label>
  <select class="form-select inputs" id="transaction-type">
      <option selected disabled>Select Type</option>
      <option value="income">Income</option>
      <option value="expense">Expense</option>
  </select>
  ```

## 🔮 Future Enhancements
![image](https://github.com/user-attachments/assets/1499fa73-c997-4b80-bbc1-cf91634f0f75)


- 💾 Implement local storage to save transactions
- 📅 Add filtering options by date or category
- 🎨 Enhance UI with animations and themes

## 📜 License

This project is open-source and available for modification and distribution.

