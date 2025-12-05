# Profile-Card
A simple React JS project demonstrating a Profile Card UI that displays user information with Props, CSS Styling, and clickable social links.

# Project Overview

This project demonstrates how to create a user info card in React using:

Props for passing user data

CSS styling for modern UI

SVG image for user profile

Dynamic social links

# Screenshots

Header + Profile Card UI
![image alt](https://github.com/happypatel200/Profile-Card/blob/9a169c09056deb8f7ad98083d59f21c8f5d22a9a/s.png)

# Functionalities

Display User Info: Name, title, email, phone, and social links.

Props Usage: User data is passed to the ProfileCard component via props.

CSS Styling: Modern card design with hover effects and responsive layout.

SVG Image: Displays user profile using inline SVG.

Clickable Links: Email, phone, and social links are clickable. Opens in a new tab.

Header/Title: Displays “Product Card” above the profile card.

# Folder Structure

profile-card/
├─ public/
│  └─ index.html
├─ src/
│  ├─ assets/
│  │   └─ user.svg
│  ├─ components/
│  │   ├─ ProfileCard.jsx
│  │   └─ ProfileCard.css
│  ├─ App.jsx
│  ├─ App.css
│  ├─ index.css
│  └─ main.jsx
├─ package.json
└─ vite.config.js

# Installation & Running
run 
npm init vite@latest . -- --template react

Navigate to the project folder
cd profile-card

Install dependencies
npm install

Start the development server
npm run dev

Open your browser at the address shown in the terminal (e.g., http://localhost:5173/).
