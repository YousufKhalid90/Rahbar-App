# Rahbar-App
# Rahbar - Mental Health Support Mobile App
Project Duration: June 2023 - August 2023
Developed By: Muhammad Yousuf Khalid during Internship at Creative Chaos

# Project Overview
Rahbar is a mobile application designed to connect users with mental health professionals. The app provides a platform for users to receive motivational content, access mental health-related articles, and schedule therapy sessions with professionals. It ensures a smooth user experience through features like social login, real-time chat, and session management.

# Features
# 1. User Onboarding
First-Time User Experience: A tutorial is shown to first-time users to guide them through the app's features.

Login State Management: Implemented using shared preferences to determine whether the tutorial should be shown or if the user should be taken directly to the login screen.
# 2. Social Login
Integration: Simplified user onboarding through firebase social login APIs, allowing users to sign in using their social media accounts.
# 3. Motivational Quotes
Dynamic Content: The homepage displays motivational quotes that change every time the user opens the app. These quotes are fetched from a RESTful API.
# 4. Mental Health Articles
Curated Content: The app provides users with mental health-related articles accessible from the homepage. These articles are also retrieved via a RESTful API.
# 5. Scheduling Therapy Sessions
Category Selection: Users can select the category of mental health they need assistance with.

Session Plans implemented using In-App Purchase: Users can choose between a 15-minute free chat, a 25-minute paid session, or a 60-minute premium session.

Push-Notifications: Once a session is scheduled, the user receives a notification saying "Finding Therapist."
# 6. Real-Time Chat
Chat Functionality: Once a therapist accepts the session, both the user and therapist are directed to a real-time chat.

Chat Timer: The chat includes a timer that is visible to the user only in the last 10 minutes of the session but is visible to the therapist throughout.

Session History: All chat sessions are stored in Firebase, maintaining a history for future reference.
# 7. Therapist App
Online/Offline Toggle: Therapists can toggle their availability status.

Request Notifications: Therapists receive notifications when a user requests a session.

Session Management: Once a therapist accepts a session, they won't receive new session requests until the current session is completed.
# 8. UI/UX Design
Design Implementation: The app’s UI/UX was implemented based on designs provided by the design team, ensuring a seamless user experience.
# Tech Stack
Frontend: Flutter

Backend: Firebase Firestore for real-time chat and session history

APIs: RESTful APIs for motivational quotes, articles, and session management

Login State Management: Shared Preferences

# Source Code Availability
The source code for the Rahbar project is proprietary and cannot be shared. However, screen recordings demonstrating the app's features and functionality are available in the video repository
