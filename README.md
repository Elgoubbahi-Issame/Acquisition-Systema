# Acquisition-Systema

# Mobile Applications Portfolio

## What I Built

I developed two mobile apps using React Native during my time at Imoha Tours. Both apps are live and being used by real customers and drivers every day. Here's what they do and how I built them.

---

## [1. eSIM Shopping App](https://drive.google.com/file/d/1PGlJh_zHJIBu4SD03uHj-h2PEEYCqHHN/view?usp=drive_link)


### What It Does
Think of it like an online store, but specifically for eSIM plans. Instead of going to a physical store to get a SIM card, travelers can just download the app, pick a data plan for the country they're visiting, pay with their credit card, and get their eSIM instantly. It's all done from their phone.

### The Cool Features I Added
- **Easy Shopping Experience**: Users can browse different data plans, compare prices, and buy what they need in just a few taps
- **Safe Payments**: I integrated Stripe so customers can pay securely with their credit cards
- **AI Chat Assistant**: Built a smart chatbot that can answer customer questions 24/7. It uses AI to understand what customers are asking and gives them helpful answers right away
- **Order History**: Users can see all their purchases and manage their active plans

### Why It Matters
Before this app, customers had to go through a more complicated process to get eSIMs. Now they can do everything from their phone in minutes. The AI assistant also means fewer support tickets for the team to handle manually, which saves everyone time.

### How I Built It
- **React Native**: So the same code works on both iPhone and Android
- **Node.js & Express**: For the backend server that handles all the logic
- **Stripe**: For processing payments securely
- **LangChain & Mistral AI**: To power the smart chatbot
- **Google Cloud**: To host everything and keep it running smoothly

---

## [2. Driver Companion App](https://drive.google.com/file/d/11s0fNDGnx6wN5DBnOFOcMvbYB9-5PNDe/view?usp=drive_link)

### What It Does
This is an app I built specifically for drivers who work for the company. When a customer books a ride or transport service, drivers get notified instantly on their phone. The app shows them where to go, how to get there, and lets them stay in touch with the office in real-time.

### The Cool Features I Added
- **Instant Job Alerts**: As soon as someone books a ride, the driver's phone buzzes with all the details
- **Built-in Navigation**: Integrated Google Maps so drivers can tap one button and get directions to pick up the customer
- **Live Tracking**: The office can see where each driver is on the map in real-time, which helps them assign jobs more efficiently
- **Quick Messaging**: Drivers can chat instantly with the dispatch team if they have questions or need to report something

### Why It Matters
Before this app, there was a lot of back-and-forth over phone calls and text messages. Drivers would miss jobs, get lost trying to find addresses, and dispatch couldn't see where everyone was. Now everything happens automatically and everyone stays connected. It's made operations way smoother.

### How I Built It
- **React Native with Expo**: Made development faster and easier, especially for testing on real devices
- **Node.js & Express**: Backend that handles all the bookings and communications
- **Socket.IO**: This is what makes the real-time magic happen - messages and updates appear instantly
- **Google Maps API**: For navigation and live location tracking
- **MongoDB**: Database where we store all the booking and driver information
- **Google Cloud**: Hosting and infrastructure

---
