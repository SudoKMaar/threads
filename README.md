# Threads

Threads is a web application that allows users to participate in discussions, interact with communities, and customize their user profiles. It is built using Next.js, React, MongoDB, Tailwind CSS, and other technologies to create a seamless and user-friendly experience.

[Live Demo of Threads](https://threads-kmaar.vercel.app/)

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- User Authentication: Users can sign up and log in to the application using Clerk authentication.
- Create Threads: Users can create new discussion threads and start conversations within communities.
- Comments: Users can add comments to existing threads to contribute to the discussion.
- Community Interaction: Users can join communities and participate in discussions within those communities.
- User Profile: Users can customize their profiles, update their profile pictures, and provide a bio.

## Prerequisites

Before running the application, make sure you have the following installed:

- Node.js (v20 or higher)
- MongoDB

## Getting Started

1. Clone the repository:

```
git clone https://github.com/SudoKMaar/threads.git
cd threads-clone
```

2. Install dependencies:

```
npm install
```

3. Set up environment variables:

Create a `.env.local` file in the root directory and add the required environment variables:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY= Clerk's public key for client-side authentication.
CLERK_SECRET_KEY= Clerk's secret key for server-side authentication.
NEXT_PUBLIC_CLERK_SIGN_IN_URL= /sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL= /sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL= /onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL= /
MONGODB_URL= MongoDB connection URL.
```

Replace keys with your actual Clerk public key, Clerk secret key, and MongoDB connection URL, respectively.

4. Start the development server:

```
npm run dev
```

The application should now be running on `http://localhost:3000`.

## Technologies Used

- Next.js: React framework with server-side rendering and static site generation capabilities.
- React: JavaScript library for building user interfaces.
- MongoDB: NoSQL database for storing application data.
- Mongoose: Object Data Modeling (ODM) library for MongoDB and Node.js.
- Tailwind CSS: Utility-first CSS framework for styling elements.
- Zod: TypeScript-first schema validation library.
- Clerk: Authentication and user management service.
- ESLint: Linter tool for identifying and fixing code errors.
- UploadThing: Library for handling file uploads.

## Contributing

Contributions to Threads Clone are welcome! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push the changes to your fork.
5. Submit a pull request to the `main` branch of the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Clerk](https://clerk.dev) for providing authentication services.
- [UploadThing](https://uploadthing.com) for handling file uploads.
- [Next.js](https://nextjs.org) for the excellent React framework.
- [Tailwind CSS](https://tailwindcss.com) for the utility-first CSS framework.
