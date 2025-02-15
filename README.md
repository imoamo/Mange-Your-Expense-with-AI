# Welth

Welth is a personal finance management application that helps you track your income and expenses efficiently. With AI-powered insights, automated email notifications, and a seamless user experience, Welth ensures you stay on top of your finances.

## Features

- **Transaction Management:** Add and manage transactions (income & expenses).
- **Dashboard Overview:** View your 5 most recent transactions.
- **Beautiful Pie Charts:** Visualize your financial data.
- **Accounts Management:** View and add new accounts.
- **Transaction Insights:** AI-powered analysis of your spending habits.
- **Automated Alerts:** Get notified when your budget exceeds 80%.
- **Monthly Reports:** Receive a summary of last month's transactions via email.
- **Image Upload & Scan:** Upload receipts and use AI to auto-fill transaction details.
- **Graphs & Trends:** View transaction history in an intuitive graph format.

## Tech Stack

### Frontend
- **Next.js** (React framework)
- **ShadCN UI** (UI components)
- **Tailwind CSS** (Styling)

### Backend & Services
- **Clerk** (Authentication & User Management)
- **Prisma** (ORM for database interactions)
- **Supabase** (PostgreSQL database)
- **Resend API** (Email notifications)
- **Gemini API** (AI-powered transaction insights & receipt scanning)
- **Arcjet** (Rate limiting and security)
- **Inngest** (Automated background jobs & workflows)

## Setup & Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/imoamo/Mange-Your-Expense-with-AI.git
   cd Mange-Your-Expense-with-AI
   ```

2. **Install dependencies**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Create a `.env` file** and add the following variables:
   ```env
   DATABASE_URL=
   DIRECT_URL=
   
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
   
   GEMINI_API_KEY=
   
   RESEND_API_KEY=
   
   ARCJET_KEY=
   ```

4. **Run the development server**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

5. **Open the application**
   Visit `http://localhost:3000` in your browser.

## Contributions

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

Enjoy managing your finances with **Welth**! 🚀
