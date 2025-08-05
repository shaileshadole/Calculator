# React Calculator App

A simple yet functional calculator built with **React** and the `useReducer` hook. This project demonstrates core React concepts including component reusability, state management with reducers, and clean UI structure using CSS.

![Calculator Screenshot](screenshot.png) <!-- Add a screenshot in your project folder with this name -->

---

## 🚀 Features

- Basic arithmetic operations: addition, subtraction, multiplication, division
- Decimal support
- Delete single digit (`DEL`)
- Clear all inputs (`AC`)
- Prevents multiple `.` or leading zeros
- Displays formatted numbers for better readability

---

## 📁 Project Structure
calculator/
├── public/
├── src/
│   ├── App.js
│   ├── DigitButton.js
│   ├── index.css
│   ├── main.js
│   ├── OperationButton.js
│   └── styles.css
├── index.html
├── package.json
├── README.md
├── screenshot.png       👈 (make sure it’s renamed like this)




---

## 🛠️ Technologies Used

- React (with functional components)
- JavaScript (ES6+)
- useReducer for state management
- CSS for styling

---

## 🧠 Key Concepts Used

- **useReducer** for managing calculator state (digits, operations, evaluations)
- **Component reuse** with `DigitButton` and `OperationButton`
- **Intl.NumberFormat** for formatting integers
- **Controlled rendering** based on operand and operation state

---

## 📦 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/your-username/react-calculator.git

# Navigate to the project directory
cd react-calculator

# Install dependencies
npm install

# Start the development server
npm start


Open http://localhost:3000 to view it in the browser.

🖼️ Preview
Add a screenshot of your calculator here by placing a file named screenshot.png in the root directory.

🙌 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📄 License
This project is open source and available under the MIT License.

✨ Acknowledgments
Inspired by the React calculator build concept explained by Web Dev Simplified and extended with features and cleaner formatting logic.

📬 Contact
Developer: Shailesh Adole
GitHub: @shaileshadole

---

### ✅ Final Step

- Rename `"your-username"` in links to your actual GitHub username.
- Add a `screenshot.png` of your calculator in the root directory for visual representation.
- If you'd like, I can also generate a `LICENSE` file for MIT.

Let me know if you want to include deployment info (like Vercel/Netlify) or dark theme support!
