# Airbnb Clone

A full-stack property marketplace inspired by Airbnb. The project demonstrates listings, authentication, reservations, image uploads, location selection, and responsive application design.

## Features

- User registration and authentication
- Property listing creation
- Image uploads with Cloudinary
- Date-based reservations
- Map and location selection
- Search and filtering
- Favorites and application state
- Responsive user interface

## Tech Stack

- Next.js
- React and TypeScript
- Prisma
- NextAuth.js
- MongoDB
- Tailwind CSS
- Cloudinary
- React Leaflet
- Zustand

## Getting Started

```bash
git clone https://github.com/jaysmartinez/airbnb-clone.git
cd airbnb-clone
npm install
```

Create a local `.env` file containing the database, authentication, and Cloudinary settings used by the application. Then initialize Prisma and start development:

```bash
npx prisma generate
npx prisma db push
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).
