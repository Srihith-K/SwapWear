# SwapWear - Clothing Exchange & Swap Marketplace

## Project details

- **Student:** Kanukolanu Venkata Sai Srihith
- **Degree:** B.Tech - Computer Science and Engineering (CSE)
- **Internship role:** Frontend Developer Intern
- **Internship period:** September 1, 2026 to December 1, 2026

## About the project

SwapWear is a web application made for people who want to exchange clothes instead of throwing away clothes that they no longer use. A user can add clothing items, look at items posted by others and send swap requests for items they are interested in.

I developed this project using React and Vite as part of my frontend development internship. The application has separate pages for browsing clothes, managing listings, viewing swap requests and other marketplace activities.

## Live website

https://tranquil-blini-58b2fc.netlify.app

## Technologies used

- React
- Vite
- JavaScript
- HTML and CSS
- React Router DOM
- Browser Local Storage
- Netlify (deployment)

## Main features

The project includes pages and interfaces for:

- User registration and login
- User dashboard and profile
- Adding, editing and deleting clothing listings
- Browsing clothing items
- Viewing clothing item details
- Wishlist
- Swap requests
- Chat
- Notifications
- Swap value calculator
- Admin section

## Project structure

```text
SwapWear/
├── public/
├── src/
│   ├── assets/
│   ├── pages/
│   ├── utils/
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── ProtectedRoute.jsx
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
```

## How to run the project on your computer

Make sure Node.js and npm are installed.

1. Download or clone this project.
2. Open the project folder in VS Code.
3. Open the terminal in that folder.
4. Install the required packages:

```bash
npm install
```

5. Start the development server:

```bash
npm run dev
```

6. Open the local URL shown in the terminal (usually `http://localhost:5173`).

## Other useful commands

Create a production build:

```bash
npm run build
```

Check the code using ESLint:

```bash
npm run lint
```

Preview the production build locally:

```bash
npm run preview
```

## Data storage

The current version uses browser Local Storage to save application data. This means the data is stored in the browser being used and is not automatically shared between different users or devices.

A cloud database and production-grade authentication have not been integrated in this version. Firebase Authentication and Cloud Firestore can be considered for a future version.

## Testing note

The add-clothing flow and checking that the new listing remains after a page refresh were reported as working during manual testing. Other test cases should be marked Pass or Fail only after they have been checked on the live website.

## Future improvements

- Connect a cloud backend so users can share marketplace data.
- Improve authentication and access control.
- Improve location-based item discovery.
- Complete and test chat, notifications and admin features.
- Add more testing for different screen sizes and user flows.
