# Personal Money Manager

A Java desktop application for managing your personal finances with professional logic.  
Features include:
- Adding/viewing incomes and expenses
- Managing savings goals
- Automatic savings allocation (percentage-based)
- Inheritance and abstraction in code structure
- GUI implemented with Java Swing
- Robust exception handling

## File Structure

```
src/
 ├── Transaction.java
 ├── Income.java
 ├── Expense.java
 ├── SavingsGoal.java
 ├── MoneyManagerLogic.java
 └── MoneyManager.java
```

## How to Run

1. **Prerequisites**  
   - Java JDK 8 or higher installed.
   - All `.java` files must be in the same directory (e.g., in a folder called `src`).

2. **Compile**

   Open a terminal in the `src` directory and run:
   ```sh
   javac *.java
   ```

3. **Run**

   Then launch the application with:
   ```sh
   java MoneyManager
   ```

   The GUI will open. Use the buttons to add incomes, expenses, savings goals, set savings percent, and view summary.

## Notes

- All logic is object-oriented, using inheritance and abstraction.
- Exception handling is provided for invalid input.
- No database is used; all data is in-memory and will be lost when the program closes.
- Extend it further for file persistence, reporting, or more advanced features!

---

**Author:** [porichoy221](https://github.com/porichoy221)
