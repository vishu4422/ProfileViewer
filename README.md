# ProfileViewer

Spring Boot backend for viewing user profiles with features like friends, groups, media, and reviews. Designed to support a mobile-style UI.

## Features
- User profile overview (bio, stats, avatar)
- Friends and groups listing
- Media (images/videos)
- Ratings and reviews with submission

## Tech Stack
- Java 17
- Spring Boot
- Spring Data JPA
- Maven

## API Endpoints
- `GET /api/profile/{userId}`
- `GET /api/profile/{userId}/friends`
- `GET /api/profile/{userId}/groups`
- `GET /api/profile/{userId}/media`
- `GET /api/profile/{userId}/reviews`
- `POST /api/profile/{userId}/reviews`

## Getting Started
```bash
git clone https://github.com/your-username/ProfileViewer.git
cd ProfileViewer
./mvnw spring-boot:run
