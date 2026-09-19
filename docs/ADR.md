# Architecture Decision Record (ADR)

## Title
FitFlow Technology Stack Decision

## Status
Accepted

## Context
FitFlow requires a cross-platform mobile application with high performance, real-time features, AI integration, secure user authentication, and scalable data handling.

## Decision
React Native will be used for the frontend, Node.js / NestJS for the backend, Firebase for the database, and Firebase Authentication for user authentication. An AI microservice will support personalized workout and nutrition features.

## Reason
This combination supports fast development, real-time features, scalability, mobile integration, and AI-based functionality.

## Consequences
The system will be easier to develop and maintain, but it may depend strongly on Firebase services.
