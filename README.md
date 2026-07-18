# LoanMe Frontend

A modern React web application serving as the frontend interface for the Loan Management System (LoanMe). 

## Overview
This frontend connects to the `loanme-backend` to provide a seamless experience for users applying for and managing loans. It features a responsive design and integrates essential tools for identity verification and payments.

## Features
- **User Authentication:** Secure JWT-based login and registration.
- **Identity Verification (KYC):** Integrated with `react-identity-kyc` for robust identity checks.
- **Payments:** Integrated with `react-paystack` for handling smooth payment transactions.
- **Modern UI:** Built with Tailwind CSS and Framer Motion for smooth, interactive animations.
- **Responsive Design:** A mobile-first approach ensuring the app works perfectly across all devices.

## Tech Stack
- **Framework:** React.js (Create React App)
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion, Lottie React
- **Routing:** React Router DOM v6
- **API Communication:** Axios
- **Payments & KYC:** React Paystack, React Identity KYC

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AbdlKabeer/loanme-frontend.git
   cd loanme-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure Environment Variables:
   Create a `.env` file in the root directory and add any necessary API keys or Backend URLs (e.g., `REACT_APP_API_URL`, Paystack keys, etc.).

4. Start the development server:
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
