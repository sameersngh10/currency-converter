
# 💱 Currency Converter App

This is a **React + Vite-based currency converter** that allows you to convert currencies in real-time using the **Fawaz Ahmed currency API**. It supports swapping currencies and displays the converted amount instantly.

---

## 🚀 **Tech Stack**
- **Frontend:** React with Vite
- **Styling:** Tailwind CSS
- **API:** [Fawaz Ahmed Currency API](https://github.com/fawazahmed0/currency-api)

---

## 📁 **Project Structure**
```
/src
 ├── /components         # Reusable components (InputBox)
 ├── /hooks              # Custom hook (useCurrencyInfo)
 ├── /assets             # Static images (if any)
 ├── App.jsx             # Main application logic
 ├── main.jsx            # Renders the app into the DOM
 ├── index.css           # Tailwind CSS imports
 ├── vite.config.js      # Vite configuration
 ├── package.json        # Project dependencies
 ├── README.md           # Project documentation
```

---

## ⚙️ **Features**
- Real-time currency conversion using live exchange rates.
- Custom hook (`useCurrencyInfo`) for API fetching.
- Swap button to interchange currencies.
- Styled with Tailwind CSS.
- Background image on the left, conversion card on the right.
- Empty input by default with `0` as placeholder.
- Removed number increment/decrement buttons.

---

## 🛠️ **Installation & Setup**

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd currency-converter
```

2. **Install dependencies**
```bash
npm install
```

3. **Start the development server**
```bash
npm run dev
```

4. **Build for production**
```bash
npm run build
```

---

## 🔥 **Usage**
- Enter the amount you want to convert.
- Select the **From** and **To** currencies.
- Click the **Convert** button to see the converted amount.
- Use the **Swap** button to interchange currencies.

---

## 🔧 **API Integration**
- The custom hook `useCurrencyInfo` fetches the latest currency rates.
- Example API call: 
```
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/{currency}.json
```
- Currency rates are extracted dynamically and displayed.

---

## 🎯 **Folder Details**

### `/components/InputBox.jsx`
- Reusable component for currency input fields.
- Allows currency selection and amount input.

### `/hooks/useCurrencyInfo.jsx`
- Custom hook to fetch and store currency conversion rates.

### `/App.jsx`
- Main application logic including state management, swapping, and rendering.

---

## 🛡️ **Error Handling & Optimizations**
- Added fallback handling if the API returns incomplete or empty data.
- Optimized `useEffect` dependencies to prevent unnecessary re-renders.
- Input field validation to prevent invalid operations.

---

## 🎯 **Future Enhancements (Optional)**
- Add currency symbols next to the amounts.
- Support for historical exchange rates.
- Dark mode styling.
- Caching for faster responses.

---

## 🛠️ **Commands**
- `npm run dev`: Start the development server.
- `npm run build`: Build the app for production.
- `npm run preview`: Preview the production build.

---
