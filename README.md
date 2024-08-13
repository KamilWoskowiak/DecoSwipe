# FurniSwipe

FurniSwipe is an AI-powered furniture recommendation app that helps users find home décor items that match their style by swiping through various options. The app uses machine learning to provide personalized suggestions based on user preferences.

## Features

- **Personalized Recommendations:** AI-driven suggestions based on user preferences.
- **Style Matching:** Find furniture that fits a person's unique design taste. 

## Tech Stack

- **Frontend:** Next.js, TypeScript
- **Backend:** Java, Spring Boot, Spring Web
- **Database:** PostgreSQL
- **AI/ML:** Deeplearning4j (DL4J) for recommendations
- **Blob Storage:** Amazon S3 for storing and serving images and media

## System Overview

### Frontend

- **Next.js**: Renders the user interface and communicates with the backend.
- **TypeScript**: Provides type safety and enhanced development experience.

### Backend

- **Spring Boot API**: Handles user interactions, furniture data, and recommendation logic.
- **AI Engine**: Processes user data to generate personalized furniture suggestions.
- **PostgreSQL**: Stores user profiles, furniture details, and interaction history.
- **Amazon S3**: Stores images and media files associated with furniture items.

### S3 Integration

- **Image Uploads:** Furniture images are uploaded to Amazon S3 via the backend API.
- **Secure Access:** Ensure secure access to S3 assets using pre-signed URLs.
- **Cost Efficiency:** Store and serve media files with S3’s scalable storage solution.
