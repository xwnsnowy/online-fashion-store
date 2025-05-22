🛍️ Fashion Store App
A modern and responsive e-commerce fashion website built with React.js, Tailwind CSS, and Strapi. This project showcases a full-stack implementation of an online shopping experience, from product browsing to secure checkout.

🚀 Features
🧑‍💻 Responsive UI with modern design and animation (Tailwind CSS + AOS)

🛒 Product Management: Add/edit/delete products (via Strapi CMS)

🔐 Authentication & Authorization: Secure login and role-based access (JWT)

💳 Shopping Cart & Checkout: Full cart flow with Stripe payment integration

🗃️ Persistent State using Redux Toolkit & redux-persist

🔍 Search & Filter for products

🌐 RESTful API integration with Axios hooks

🧱 Tech Stack
Frontend	Backend	Others
React.js (Vite)	Strapi (Node.js)	Redux Toolkit, redux-persist
Tailwind CSS	RESTful API	Axios, Stripe API
AOS (Scroll Anim.)	MongoDB	JWT Auth

📸 Demo

🔗 Live site: Coming Soon

📦 Installation
bash
Copy
Edit
# Clone the repo
git clone https://github.com/xwnsnowy/online-fashion-store.git
cd online-fashion-store

# Install frontend dependencies
npm install

# Run the app
npm run dev
💡 Make sure you have Strapi running on a separate server with proper API endpoints configured.

📁 Folder Structure (Frontend)
bash
Copy
Edit
├── src
│   ├── components      # Reusable UI components
│   ├── pages           # Pages with routing (Vite or React Router)
│   ├── redux           # State management setup
│   ├── hooks           # Custom hooks (e.g., Axios)
│   ├── utils           # Helper functions
│   └── assets          # Images, fonts, etc.
✅ To-Do / Improvements
 Add unit tests with React Testing Library

 Admin dashboard (React-based)

 Multi-language support (i18n)

 Product reviews & ratings

🙌 Author: Nguyen Tien Thanh
📧 xwnsnowy.dev@gmail.com
🌐 LinkedIn
💻 Portfolio (optional)

📄 License
This project is open-source and available under the MIT License.
