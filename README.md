FinTrack: Modern Personalized Finance Dashboard

FinTrack is a single-page, responsive web application designed to help users track their personal finances, manage debt, set savings goals, and receive personalized advice based on their spending habits. It uses the power of the Gemini API to add intelligent features like budget advice and receipt scanning.

 Key Features

FinTrack goes beyond basic budgeting with the following integrated tools:

1.  Personal Finance Tracker

Custom Budgeting: Easily add, edit, and remove custom spending categories and allocate amounts.

Real-time Visualization: An interactive Doughnut Chart instantly updates to show the breakdown of all spending categories and the remaining monthly savings.

Quick Stats: Displays live calculations for Total Spending, Monthly Savings, and Remaining Budget.

2. Debt & Synchronization Tracker

Debt Management: Track multiple credit cards and loans, including current balances and annual interest rates.

Simulated Payments: Easily log payments made toward debts to reduce the outstanding balance.

Spending-to-Debt Sync (Unique Feature): Simulate making a purchase on credit. You can select an existing spending category and sync its entire amount to a selected debt, resetting the category amount to ₹0 in the budget while increasing the card balance.

3. Savings Goals Tracker

Set specific financial goals with target amounts (e.g., Emergency Fund, New Home).

Visualize progress with dynamic percentage bars that update instantly when saved amounts are modified.

4. User Experience

Currency: All amounts are displayed in Indian Rupees (₹).

Theming: A persistent Dark/Light Mode toggle in the header adapts the UI to the user's preference.

Responsiveness: The layout is fully optimized for all devices (mobile, tablet, and desktop).

 Technologies Used

Frontend: HTML5, JavaScript and CSS3

Styling: Tailwind CSS for responsive design and modern aesthetics.

Data Visualization: Chart.js for the interactive spending and savings pie chart.

Intelligence Layer: Gemini API for sophisticated text generation (budget advice) and image understanding (receipt scanning).

 How to Use

Since this is a single self-contained HTML file, running the application is simple:

Save the code as index.html.

Open index.html in any modern web browser.

Important Note on AI Features:
The Budget Advice and Receipt Scanner rely on calling the Gemini API. These simulated features require the execution environment to allow external API calls to function correctly.
