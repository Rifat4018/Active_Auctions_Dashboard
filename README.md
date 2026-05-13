# React + Vite

# Active Auctions Dashboard

A frontend React application designed for discovering, tracking, and managing auction items. Users can browse active auctions, bookmark their favorite items, and dynamically track the total financial commitment of their selected bids. 

## 🚀 Key Features

* **Interactive Auction Feed:** Browse a list of active auction items (driven by the `Blogs` component).
* **Favorites Management:** Users can add items to their "Favorite Items" list using a heart icon.
* **Dynamic Cart/Bid Calculation:** The dashboard automatically calculates and updates the "Total Bids Amount" as items are added or removed from the favorites list.
* **Real-time Notifications:** Integrated `react-toastify` to provide immediate user feedback (e.g., when an item is successfully removed from favorites).
* **Responsive UI:** Styled utility-first with Tailwind CSS v4 and DaisyUI components for a clean, modern interface.

## 🛠️ Technology Stack

* **Framework:** React 19 + Vite
* **Styling:** Tailwind CSS v4, DaisyUI
* **Icons:** React Icons (`react-icons`)
* **Notifications:** React Toastify (`react-toastify`)

## ⚙️ Installation & Setup

To run this project locally:

1.  **Clone the repository** (or download the source code).
2.  **Install dependencies:**
    Make sure you are in the project root directory where `package.json` is located, then run:
    ```bash
    npm install
    ```
3.  **Start the development server:**
    ```bash
    npm run dev
    ```
4.  Open your browser and navigate to the localhost URL provided in your terminal (usually `http://localhost:5173`).

## 📁 Project Structure (Key Files)

* `src/App.jsx`: Main application state holding the `mark` (favorites array) and `price` (total bid amount).
* `src/Components/`: Contains the modular UI components (`Navbar`, `Banner`, `Blogs`, `Footer`).

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
