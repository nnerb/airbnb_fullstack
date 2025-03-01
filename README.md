# Airbnb Clone

A full-stack Airbnb clone built using modern web technologies, including Next.js, MongoDB, Prisma, Tailwind CSS, React.js, and NextAuth for authentication.

## Tech Stack

- **Frontend:** Next.js, React.js, Tailwind CSS
- **Backend:** Next.js API routes, Prisma, MongoDB
- **Authentication:** NextAuth (Google & GitHub OAuth)
- **Deployment:** Vercel

## Features

- User Authentication (Register, Login, Social Login with Google & GitHub)
- Responsive UI built with Tailwind CSS
- Listing creation with multiple steps:
  - Category selection
  - Location selection with interactive map
  - Guest count selection
  - Image upload via Cloudinary
  - Description and pricing
- Fetching and displaying listings using server components
- Favoriting functionality
- Individual listing view
- Reservation system (booking trips, managing guest reservations)
- User-specific screens for managing listings, favorites, and reservations
- Advanced filtering options for listings
- Deployment on Vercel

## Installation & Setup

### Prerequisites
Make sure you have the following installed:
- Node.js (latest LTS recommended)
- MongoDB (local or Atlas cloud instance)

### Clone the Repository
```bash
git clone https://github.com/your-username/airbnb-clone.git
cd airbnb-clone
```

### Install Dependencies
```bash
npm install
```

### Environment Variables
Create a `.env` file in the root directory and add the following:
```env
DATABASE_URL="your_mongodb_connection_string"
NEXTAUTH_SECRET="your_nextauth_secret"
GITHUB_ID="your_github_client_id"
GITHUB_SECRET="your_github_client_secret"
GOOGLE_CLIENT_ID="your_google_client_id"
GOOGLE_CLIENT_SECRET="your_google_client_secret"
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="your_cloudinary_cloud_name"

```

### Run the Development Server
```bash
npm run dev
```
The app should now be running on `http://localhost:3000`


## Deployment
To deploy on Vercel, run:
```bash
vercel
```
Follow the setup instructions and your app will be live!

## Inspiration
Inspo! Here's the link: [YouTube Video](https://www.youtube.com/watch?v=c_-b_isI4vg)

## Contributing
Feel free to fork the repo and submit pull requests.

## License
MIT License
