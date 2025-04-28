# Personal Finance Visualizer

A web application for tracking income and expenses with data visualization capabilities.

## Features

- Add, edit, and delete transactions
- Categorize transactions as income or expense
- Visualize monthly expenses with interactive charts
- Responsive design for all screen sizes

## Technologies Used

- Next.js (React)
- Node.js
- MongoDB
- Shadcn/ui
- Recharts
- Zod for validation
- React Hook Form


## Implementation Notes

1. **Database**: The application uses MongoDB with Mongoose for data persistence. Transactions are stored with amount, date, description, type (income/expense), and category.

2. **API**: Next.js API routes handle all CRUD operations for transactions with proper error handling.

3. **UI**: Shadcn/ui components provide a consistent and modern interface. The application includes:
   - A form for adding/editing transactions with validation
   - A table displaying all transactions
   - A bar chart showing monthly expenses

4. **Validation**: Zod is used for both frontend and backend validation to ensure data integrity.

5. **Responsive Design**: The layout adapts to different screen sizes using Tailwind CSS.

6. **Data Visualization**: Recharts is used to create interactive charts that help users visualize their spending patterns.

This implementation meets all the requirements specified in the assignment, providing a complete personal finance tracking solution with visualization capabilities.
