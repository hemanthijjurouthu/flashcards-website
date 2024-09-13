# Flashcard Learning Tool

## Overview
A simple flashcard learning tool built with React.js for the frontend and Node.js with Express for the backend. It allows users to view flashcards, flip them to reveal answers, and navigate between them. Admins can manage flashcards through an internal dashboard.

## Frontend
- **React.js**: Used for building the user interface.
- **Components**:
  - Flashcard: Displays flashcards and supports flipping.
  - AdminDashboard: Allows admins to add, edit, and delete flashcards.

## Backend
- **Node.js with Express**: Provides APIs to manage flashcards.
- **Endpoints**:
  - GET /flashcards: Retrieve all flashcards.
  - POST /flashcards: Add a new flashcard.
  - PUT /flashcards/:id: Edit an existing flashcard.
  - DELETE /flashcards/:id: Delete a flashcard.

## Storage
- Flashcards are stored in a JSON file ("flashcards.json").

## Setup

### Backend
1. Clone the repository.
2. Navigate to the backend directory.
3. Install dependencies:

   npm install
