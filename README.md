# File Chat Frontend

A chat application that allows users to interact with PDF documentation using Langchain, FastAPI, React.js, and Gemini Pro.

## Overview

This application enables users to:
- Upload PDF documents
- Chat with an AI assistant about the document contents
- Get contextual responses based on the document's information
- Navigate through chat history

## Architecture

The application consists of two main components:

### Frontend (React.js)
- Single Page Application built with React
- Material-UI for component styling
- Real-time chat interface
- File upload functionality
- Chat history management

### Backend (FastAPI)
- REST API built with FastAPI
- PDF processing using Langchain
- Integration with Google's Gemini Pro for AI responses
- Document storage and management
- Chat history persistence

## Setup Instructions

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository.
2. Navigate to the frontend directory.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
