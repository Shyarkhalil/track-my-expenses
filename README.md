
# Building ExpenseList

## Description
Building ExpenseList is a simple expense tracker mini-project built with React. It allows users to add new expenses using a form at the top of the page. The form includes validation to ensure that values are entered before submitting. Once an item is added, it appears in the list of expenses below, and the form is cleared for new entries.

Users can filter the expenses by category, and the list updates accordingly. Each item in the list displays the description, amount, and total. The user can also delete an item using the delete button. This project serves as a fantastic way to practice and improve React skills.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shyarkhalil/track-my-expenses.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd track-my-expenses
   ```

3. **Install the dependencies:**
   ```bash
   npm install
   ```

4. **Start the development server:**
   ```bash
   npm start
   ```

Once the server is running, the app will be available at `http://localhost:3000`.

## Usage
Once the project is up and running on `http://localhost:3000`, follow these steps to use the "Building ExpenseList" app:

1. **Add an Expense:**
   - At the top of the page, you’ll see a form to add a new expense.
   - Enter the description and amount in the form fields.
   - If you try to submit the form without filling in the required fields, validation messages will appear.
   - After entering values, click the "Submit" button to add the expense to the list. The form will be cleared after submission.

2. **Filter Expenses:**
   - Below the form, you will see a list of all expenses.
   - Use the category filter to display expenses from a specific category. The list will automatically update to reflect your selection.
   
3. **Delete an Expense:**
   - Each item in the list has a "Delete" button. Click on it to remove the corresponding expense from the list.

## Features
- **Add Expenses:** Users can add new expenses by entering a description and amount in the form.
- **Form Validation:** If the form is submitted without filling in required fields, validation messages will be displayed.
- **Expense Filtering:** Users can filter the list of expenses by different categories (All, Utilities, Groceries, Entertainment).
- **Delete Expenses:** Each expense item has a delete button for easy removal.

## Technologies Used
- **React:** For building the user interface.
- **TypeScript:** Provides static typing for improved code quality.
- **Bootstrap:** Used for styling and layout.
- **Zod:** For form validation.
- **Cypress:** For end-to-end testing.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

Please ensure your code follows best practices and includes appropriate documentation or comments where necessary. All contributions will be reviewed before merging. Thank you for contributing!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
