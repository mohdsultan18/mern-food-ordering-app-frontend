🍽️ MERN Food Ordering App – Feature Summary
🖥️ Landing Page
Modern, responsive design with a hero section and city/town search form.

Includes auth links, app branding, and visually rich imagery.

Fully responsive layout with mobile drawer menu navigation.

🔐 User Authentication
Auth0 integration for secure login/signup.

Multiple sign-in methods:

Email & password

Google OAuth

Features include:

Forgot password

Email confirmation

Post-login navbar updates with:

Username display

User avatar

Access to user-specific routes

👤 User Profile Management
View and update personal details:

Name

Email

Address

Pre-fills checkout form with saved user info for convenience.

🍴 Restaurant Management (Admin Features)
Add and manage a restaurant as an owner.

Set restaurant details and cuisines.

CRUD operations for menu items.

Upload restaurant images for search results visibility.

🔍 Search & Discovery
City/town-based search functionality.

Results show:

Number of available restaurants

Best matches based on search query

Filters:

Cuisine type (e.g., Café)

Sorting:

By estimated delivery time

Fully responsive results grid for all screen sizes.

🏪 Restaurant Detail Page
Detailed view of the selected restaurant.

Basket/Cart functionality on the side:

Add/remove items

Live calculation of total price

💳 Checkout & Payment
Pre-filled delivery details from user profile.

Integrated with Stripe for secure payments.

Real-time cart summary with:

Total amount

Item breakdown

Delivery fee

🚚 Order Tracking
Redirected to Order Status Page post-payment.

Displays:

Order summary

Live status updates

Real-time status sync between restaurant dashboard and customer order view.

📦 Restaurant Dashboard (Order Management)
Notifications for new orders.

Option to update order status (e.g., "Out for delivery").

Real-time order status push to customer interface.
