# Podcaster AI

Podcaster AI is a cutting-edge application that enables users to generate and manage AI-driven podcasts. It utilizes OpenAI's text and image generation capabilities along with text-to-speech (TTS) to create high-quality, AI-generated content. The platform is built using Next.js and Tailwind CSS for a seamless UI/UX, with MongoDB as the database and Clerk for authentication.

## Features

- **AI-Generated Content**: Uses OpenAI for text and image generation.
- **Text-to-Speech (TTS)**: Converts AI-generated text into human-like speech.
- **User Authentication**: Secured with Clerk.
- **Credit System**: Implements Stripe for handling credits and transactions.
- **Logo Editing Tools**:
  - Image Restore
  - Generative Fill
  - Object Remove
  - Object Recolor
  - Background Remove

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: MongoDB, Node.js
- **Authentication**: Clerk
- **Payments**: Stripe
- **AI Services**: OpenAI (text & image generation, TTS)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/podcaster-ai.git
   cd podcaster-ai
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-api>
   MONGODB_URI=<your-mongodb-uri>
   STRIPE_SECRET_KEY=<your-stripe-secret-key>
   OPENAI_API_KEY=<your-openai-api-key>
   ```
4. Run the development server:
   ```sh
   npm run dev
   ```

## Usage

- Sign up or log in using Clerk authentication.
- Generate podcast scripts using AI.
- Convert text into speech with AI-powered TTS.
- Customize podcast visuals with AI-powered image generation.
- Manage AI credits through Stripe integration.

## Credits

Podcaster AI integrates the following third-party services:

- **OpenAI** for text generation, image generation, and text-to-speech.
- **Stripe** for handling payments and credit transactions.
- **Clerk** for authentication.

## Acknowledgment

This project was inspired by **JS Mastery** and its contributions to the developer community.

## Contact

For questions or suggestions, reach out to Yichen at snowsyc524@gmail.com.
