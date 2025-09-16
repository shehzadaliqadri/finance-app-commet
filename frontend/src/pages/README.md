# Pages Directory

This directory contains all page-level components that represent different routes/screens in the application.

## Structure

### Authentication Pages
- Login
- Register
- ForgotPassword
- ResetPassword

### Dashboard Pages
- Dashboard (main overview)
- Analytics
- Reports

### Finance Management Pages
- Transactions
- Budget
- Categories
- Accounts

### Profile & Settings
- Profile
- Settings
- Notifications

### Error Pages
- NotFound (404)
- ServerError (500)
- Unauthorized (403)

## Naming Convention

- Use PascalCase for page names
- Page files should have `.jsx` or `.js` extension
- Include corresponding `.css` files for page-specific styling
- Each page should be in its own directory for better organization

## Example Structure

```
pages/
├── Auth/
│   ├── Login/
│   │   ├── Login.jsx
│   │   └── Login.css
│   ├── Register/
│   │   ├── Register.jsx
│   │   └── Register.css
│   └── ForgotPassword/
│       ├── ForgotPassword.jsx
│       └── ForgotPassword.css
├── Dashboard/
│   ├── Dashboard.jsx
│   └── Dashboard.css
├── Transactions/
│   ├── Transactions.jsx
│   └── Transactions.css
├── Budget/
│   ├── Budget.jsx
│   └── Budget.css
└── Error/
    ├── NotFound/
    │   ├── NotFound.jsx
    │   └── NotFound.css
    └── ServerError/
        ├── ServerError.jsx
        └── ServerError.css
```

## Page Component Structure

Each page component should:

1. **Import necessary dependencies and components**
2. **Define the page component as a functional component**
3. **Handle any page-specific state management**
4. **Return JSX with proper semantic structure**
5. **Export the component as default**

## Best Practices

- Keep pages focused on layout and orchestration
- Move complex business logic to custom hooks or services
- Use React Router for navigation between pages
- Implement proper SEO meta tags for each page
- Handle loading and error states appropriately
- Ensure pages are responsive and accessible
