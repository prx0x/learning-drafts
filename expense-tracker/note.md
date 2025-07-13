# 💸 Expense Tracker

This is an early prototype of a terminal-based expense tracker built using:

- Python OOP
- NumPy for array-based data handling
- Date modules for managing entries

---

## 📌 Features

- Add expense entries using OOP constructor (date, amount, category_code)
- Shortcut input support for `"today"` and `"yesterday"` (auto-fills date)
- In-memory storage of all expenses using a class-level NumPy-compatible array
- Detailed __repr__ output for better readability of each expense
- View all transactions with `transaction_history()`
- Total expense calculation using `np.sum()`
- Sorting by amount (ascending/descending) with `sort_asc()` and `sort_dsc()`
- Filter and sort large transactions over a threshold (`default ₹1000`) with `show_big_expenses()`
- Sort by date — newest first `(sort_date_latest)` or oldest first `(sort_date_oldest)`
- Export transaction history to CSV file using `export_all()`
- Operator overloading (+) to add two expenses by their amounts
- Category code tagging (integer-based, currently raw)
- Manual `.showDetails()` method for individual entries

---

## ⚠️ Limitations

- Categories are numeric codes (no human-readable tags yet)
- Not yet ready for non-technical users (not User Friendly)

---

## 🧠 Why This Exists

This was my **first learning-phase project** after learning Python basics and NumPy.  
I built it from scratch to practice:

- OOP concepts
- Debugging real data flow
- Using NumPy in applied contexts

