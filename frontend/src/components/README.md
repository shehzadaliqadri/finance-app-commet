# Components Directory

This directory contains all React components organized by functionality.

## Structure

### Layout Components
- Header
- Footer
- Sidebar
- Navigation

### UI Components
- Buttons
- Forms
- Modals
- Cards
- Tables

### Business Logic Components
- TransactionForm
- BudgetTracker
- ExpenseChart
- IncomeTracker
- FinancialSummary

### Common Components
- Loading spinners
- Error boundaries
- Toast notifications

## Naming Convention

- Use PascalCase for component names
- Component files should have `.jsx` or `.js` extension
- Include corresponding `.css` or `.module.css` files for styling
- Use descriptive, self-documenting names

## Example Structure

```
components/
├── Layout/
│   ├── Header/
│   │   ├── Header.jsx
│   │   └── Header.css
│   └── Sidebar/
│       ├── Sidebar.jsx
│       └── Sidebar.css
├── UI/
│   ├── Button/
│   │   ├── Button.jsx
│   │   └── Button.css
│   └── Card/
│       ├── Card.jsx
│       └── Card.css
└── Business/
    ├── TransactionForm/
    │   ├── TransactionForm.jsx
    │   └── TransactionForm.css
    └── BudgetTracker/
        ├── BudgetTracker.jsx
        └── BudgetTracker.css
```
