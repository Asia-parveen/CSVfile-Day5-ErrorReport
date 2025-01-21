#Marketplace Bulider Hackathon 2025 Day5:
#Day5-Task: Testing Error Handling and Backend Integration Refinment Document.
#E-Commerce Website with Next.js and Sanity CMS
This project is an e-commerce platform built during Day 5 of a hackathon. The application is designed using Next.js for the frontend and Sanity CMS for content management. The platform includes a range of features like product fetching, dynamic cart management, error handling, and optimized loading states.

#Features
#1. Dynamic Product Management
Products are fetched dynamically from Sanity CMS.
Real-time updates in the CMS reflect directly on the website.
#2. API Integration
APIs are used to fetch product data from Sanity CMS.
Handled scenarios like network issues or missing product data gracefully with error messages and fallback content.
#3. Cart Management
Add, remove, and update products in the cart.
Persistent cart data using browser storage (local storage or session storage).
Validation for product quantities to ensure accurate cart updates.
#4. Error Handling
Implemented user-friendly error messages for:
Product Not Found: Displayed when a product is missing from the database.
API Errors: Clear feedback to users when API calls fail due to network issues.
Cart Management Errors: Prevent invalid operations like adding out-of-stock products.
@5. Loading States
Skeleton loaders and spinners for a smooth user experience while fetching data.
Different loading indicators for:
Product pages.
Cart operations.
API interactions.
