# BD Room

This is an Airbnb/OYO clone built with Next.js, TypeScript, Tailwind CSS, MongoDB, Prisma, Next auth, Leaflet and many other technologies.

## Features

- User registration and authentication
- Property listing and browsing
- Property booking and reservations
- Search and filtering of properties
- Interactive map using Leaflet to display property locations

## Demo

You can check out a live demo of the Airbnb clone project [here](https://airbnb-clone-phi-green.vercel.app/).


## Prerequisites

Make sure you have the following software installed on your system:

- git If you want to clone the project from GitHub and work with it locally, you will need to have Git installed on your system. You can download and install Git from the official website (https://git-scm.com/).

- Node.js Application requires Node.js to be installed on your system in order to run. You can download and install the latest version of Node.js from the official website (https://nodejs.org/).

## Installation

- Clone the repository:

  ```
  git clone "link"
  ```

- Navigate to the project directory:

  ```
  cd "folder name"
  ```

- Install the dependencies:

  ```
  npm install
  ```

- Set up the environment variables:

  1.  Create a `.env.local` file in the root directory.

  2.  Add the following variables to the .env file, replacing the placeholder values with your own:

      ```
      DATABASE_URL=<your-mongodb-uri>
      GITHUB_CLIENT_ID=<your-github-client-id>
      GITHUB_CLIENT_SECRET=<your-github-client-secret>
      GOOGLE_CLIENT_ID=<your-google-client-id>
      GOOGLE_CLIENT_SECRET=<your-google-client-secret>
      NEXTAUTH_SECRET=<your-nextauth-secret>
      EDGE_STORE_ACCESS_KEY=<your-edge-store-access-key>
      EDGE_STORE_SECRET_KEY=<your-edge-store-secret-key>
      ```

  ```

  ```

## Usage

- Start the development server:

  ```
  npm run dev
  ```

- Open your browser and visit `http://localhost:3000` to access the application.

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes to the new branch.
- Open a pull request back to the main repository, including a description of your changes.
