# Neural Nexus

## Description

Neural Nexus is a web application that allows users to create, edit, and delete prompts. Users can log in using Google authentication through NextAuth. The home page displays prompts from all users, and users can view their profiles or profiles of other users.

## Technologies Used

- **Frontend:**
  - React
  - Tailwind CSS
  - Next
  - Next-Auth
  - Mongoose
  - Mongoose

## Features

- **User Authentication:**

  - Users can log in using Google authentication provided by NextAuth.

- **Prompts Management:**

  - Create, edit, and delete prompts.

- **Home Page:**

  - Displays prompts from all users.

- **User Profiles:**
  - View your profile.
  - View profiles of other users.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/0xOmarAdel/neural-nexus.git
   cd neural-nexus
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environmental variables:
   Create a `.env` file in the root directory with the following:

   ```env
   GOOGLE_CLIENT_ID=your-google-client-id
   GOOGLE_CLIENT_SECRET=your-google-client-secret
   MONGODB_URL=your-mongodb-connection-string
   NEXTAUTH_URL=http://localhost:3000
   NEXTAUTH_INTERNAL=http://localhost:3000
   NEXTAUTH_SECRET=your-secret-string
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

   The application will be accessible at http://localhost:3000.
