# Utils Directory

This directory contains utility functions, helper methods, constants, and other reusable code that can be used across the entire application.

## Structure

### API Utilities
- API client configuration
- Request/Response interceptors
- Error handling utilities
- Authentication helpers

### Data Formatting & Validation
- Currency formatters
- Date/time utilities
- Number formatters
- Input validation functions
- Data transformation helpers

### Financial Calculations
- Budget calculations
- Expense categorization
- Interest calculations
- Financial reporting utilities

### Common Utilities
- Local storage helpers
- Environment configuration
- Logging utilities
- Browser detection

## Files Structure

```
utils/
├── api/
│   ├── client.js
│   ├── auth.js
│   └── endpoints.js
├── formatters/
│   ├── currency.js
│   ├── date.js
│   └── number.js
├── validators/
│   ├── forms.js
│   ├── financial.js
│   └── user.js
├── calculations/
│   ├── budget.js
│   ├── expenses.js
│   └── interest.js
├── storage/
│   ├── localStorage.js
│   └── sessionStorage.js
├── constants/
│   ├── api.js
│   ├── app.js
│   └── financial.js
└── helpers/
    ├── common.js
    ├── debug.js
    └── environment.js
```

## Naming Convention

- Use camelCase for function names
- Use UPPER_SNAKE_CASE for constants
- File names should be descriptive and in camelCase
- Group related utilities in subdirectories
- Export functions as named exports for better tree-shaking

## Best Practices

1. **Pure Functions**: Make utility functions pure (no side effects) when possible
2. **Documentation**: Add JSDoc comments for all utility functions
3. **Testing**: Include unit tests for complex utility functions
4. **Error Handling**: Implement proper error handling and validation
5. **Type Safety**: Use TypeScript or PropTypes for better type safety
6. **Performance**: Consider memoization for expensive calculations

## Example Utility Functions

### Currency Formatter
```javascript
// utils/formatters/currency.js
export const formatCurrency = (amount, currency = 'USD') => {
  return new Intl.NumberFormat('en-US', {
    style: 'currency',
    currency: currency,
  }).format(amount);
};
```

### Date Utilities
```javascript
// utils/formatters/date.js
export const formatDate = (date, format = 'short') => {
  return new Intl.DateTimeFormat('en-US', {
    dateStyle: format,
  }).format(new Date(date));
};
```

### Validation
```javascript
// utils/validators/financial.js
export const validateAmount = (amount) => {
  const num = parseFloat(amount);
  return !isNaN(num) && num > 0;
};
```
