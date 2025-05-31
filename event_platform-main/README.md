# Event Management Platform

This is a full-stack event booking platform I built using Next.js 14, TypeScript, MongoDB, and Stripe. It allows users to create, browse, and manage events, and purchase tickets through a secure checkout flow.

## Tech Stack

- Frontend: Next.js 14, TypeScript, TailwindCSS, Shadcn UI
- Backend: Server Actions, MongoDB, Zod
- Auth: Clerk
- Payments: Stripe
- Uploads: UploadThing

## Features

- User authentication (Clerk)
- Event creation, update, and deletion
- View events and purchase tickets
- Search and filter events by name/category
- Responsive UI with smooth UX
- Secure checkout with Stripe
- View orders and manage events in profile

## Getting Started

1. Clone the repo
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. Install dependencies
   npm install

3. Add your environment variables

   Create a `.env` file in the root and fill in:

   NEXT_PUBLIC_SERVER_URL=
   CLERK_SECRET_KEY=
   MONGODB_URI=
   STRIPE_SECRET_KEY=
   NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=

4. Run the app
   npm start

## Notes

I used this project to learn about integrating Stripe with server actions, handling file uploads, and structuring a full-stack app using modern Next.js features. Let me know if you have feedback or questions!

