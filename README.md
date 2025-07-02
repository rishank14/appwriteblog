# Blogify — A Real-Time Blogging Web App

**Blogify** is a full-featured, responsive blogging platform built with **React** and powered by **Appwrite** as the backend-as-a-service (BaaS). It allows users to create, edit, and publish rich blog posts with real-time features like live slug generation, rich text editing, and instant content rendering.

---

## Features

- Secure Auth: Signup and login flows using Appwrite authentication  
- Rich Text Editor: Create blog content using a real-time TinyMCE editor  
- Live Slug Generator: Instantly converts blog titles into URL-friendly slugs  
- Post Management: Add, edit, delete, and view blog posts  
- Blog Feed: See all published blogs in a clean, responsive layout  
- Routing & Protection: Public/private routes using React Router and layout wrappers  
- State Management: Redux Toolkit used for consistent global state  
- Fast & Responsive UI: Built with optimized React components and form handling  

---

## Tech Stack

- Frontend: React 18  
- Backend: Appwrite (Auth, Database, Storage)  
- Editor: TinyMCE via `@tinymce/tinymce-react`  
- Routing: `react-router-dom`  
- Forms: `react-hook-form`  
- State Management: `@reduxjs/toolkit`, `react-redux`  
- HTML Rendering: `html-react-parser`  

---

## How It Works

- Users sign up or log in using Appwrite's authentication system  
- Blog posts are created through a rich text editor and stored in Appwrite’s database  
- Slugs are generated automatically in real-time from post titles to form clean URLs  
- Blog content (including HTML) is rendered safely using `html-react-parser`  
- Appwrite handles all backend tasks: authentication, data storage, and media uploads  

---

## Acknowledgements

- [Appwrite](https://appwrite.io/) – Powerful backend-as-a-service  
- [TinyMCE](https://www.tiny.cloud/) – Rich text editor  
- [React](https://reactjs.org/), [Redux Toolkit](https://redux-toolkit.js.org/), [React Router](https://reactrouter.com/)
