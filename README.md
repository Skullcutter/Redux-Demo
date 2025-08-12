# 🏦 React-Redux Bank ⚛️

A modern banking application built with React and Redux that demonstrates state management patterns, async operations, and real-time currency conversion. This project showcases both classic Redux patterns and modern Redux Toolkit implementation.

## 🌟 Key Features

- **Customer Management**: Create new customer accounts with validation.

- **Account Operations**: Deposit, withdraw, and balance tracking.

- **Multi-Currency Support**: Real-time currency conversion (USD, EUR, GBP).

- **Loan System**: Request and manage loans with purpose tracking.

- **Real-time Balance**: Live balance updates with formatted currency display.

- **Loading States**: Async operation handling with loading indicators.

- **Redux DevTools**: Full debugging support with Redux DevTools extension.

- **Modern Redux**: Implementation using Redux Toolkit (RTK).

- **Legacy Redux**: Classic Redux patterns for comparison (v1 files).

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher).
- npm or yarn package manager.

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/react-redux-bank.git
   cd react-redux-bank
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**

   ```bash
   npm start
   # or
   yarn start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to view the app.

## 📁 Project Structure

```
src/
├── features/
│   ├── accounts/
│   │   ├── AccountOperations.js    # Account transaction UI
│   │   ├── BalanceDisplay.js       # Balance display component
│   │   └── accountSlice.js         # Account state management
│   └── customers/
│       ├── CreateCustomer.js       # Customer creation form
│       ├── Customer.js             # Customer display component
│       └── customerSlice.js        # Customer state management
├── App.js                          # Main application component
├── index.js                        # App entry point with Provider
├── store.js                        # Redux Toolkit store configuration
├── store v1.js                     # Classic Redux store (legacy)
└── index.css                       # Global styles
```

## 🎮 How to Use

### Creating an Account

1. Enter your full name and national ID.

2. Click "Create new customer" to set up your account.

### Managing Your Account

- **Deposit**: Enter amount, select currency, and deposit funds.

- **Withdraw**: Enter amount to withdraw from your balance.

- **Request Loan**: Specify loan amount and purpose.

- **Pay Loan**: Repay your existing loan.

### Currency Conversion

- Select different currencies (USD, EUR, GBP) for deposits.

- Real-time conversion rates are fetched from Frankfurter API.

- Loading states show during currency conversion.

## 🎯 Learning Objectives

This project demonstrates several important React and Redux concepts:

### Redux Concepts

- **Redux Toolkit (RTK)**: Modern Redux with simplified syntax.

- **createSlice**: Reducer and action creation with RTK.

- **configureStore**: Store setup with RTK.

- **Async Thunks**: Handling async operations with middleware.

- **Redux DevTools**: Debugging and time-travel debugging.

- **Classic Redux**: Traditional patterns for comparison.

### React-Redux Integration

- **useSelector**: Reading state from Redux store.

- **useDispatch**: Dispatching actions to update state.

- **connect**: Higher-order component pattern (legacy approach).

- **Provider**: Making store available to components.

### Advanced Patterns

- **Prepare Callback**: Custom action payload preparation.

- **Async Action Creators**: Thunk middleware for API calls.

- **Loading States**: Managing async operation states.

- **Conditional Rendering**: UI updates based on state.

- **Form Handling**: Controlled components with Redux.

### API Integration

- **REST API**: Fetching real-time currency exchange rates.

- **Error Handling**: Graceful handling of API failures.

- **Async/Await**: Modern async JavaScript patterns.

## 🛠️ Technologies Used

- **React 18**: Latest React with hooks.

- **Redux Toolkit**: Modern Redux state management.

- **React-Redux**: Official React bindings for Redux.

- **Redux Thunk**: Middleware for async actions.

- **Redux DevTools**: Development debugging tools.

- **Frankfurter API**: Real-time currency exchange rates.

- **JavaScript (ES6+)**: Modern JavaScript features.

- **CSS3**: Modern styling with system fonts.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project

2. Create your feature branch (`git checkout -b feature/AmazingFeature`)

3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)

4. Push to the branch (`git push origin feature/AmazingFeature`)

5. Open a Pull Request

## 📚 Resources

- [Redux Toolkit Documentation](https://redux-toolkit.js.org/)

- [React-Redux Documentation](https://react-redux.js.org/)

- [Frankfurter API](https://www.frankfurter.app/)

- [Redux DevTools Extension](https://github.com/reduxjs/redux-devtools)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Redux team for the excellent state management library.

- React team for the amazing framework.

- Frankfurter for the free currency conversion API.

- Redux DevTools team for debugging capabilities.
