# PromptCast

## 🤖 Introduction

PromptCast is a cutting-edge AI SaaS platform that enables users to create, discover, and enjoy podcasts with advanced features like text-to-audio conversion with multi-voice AI, podcast thumbnail generation, and seamless playback.


## ⚙️ Tech Stack

- **Frontend**: Next.js 14, TypeScript, Tailwind CSS
- **Backend**: Convex (Database & Backend)
- **Authentication**: Clerk
- **AI Services**: OpenAI
- **UI Components**: ShadCN

## 🔋 Features

- **Authentication**: Secure user login and registration
- **Home Page**: Trending podcasts with sticky player
- **Discover**: Explore new and popular podcasts
- **Search**: Find podcasts with various criteria
- **Create Podcast**: Text-to-audio conversion with AI image generation
- **Multi Voice AI**: Multiple AI-generated voices
- **Profile Management**: View and manage created podcasts
- **Podcast Details**: Detailed information with creator details
- **Audio Player**: Advanced controls with backward/forward and mute/unmute
- **Responsive Design**: Works across all devices

## 🚀 Quick Start

### Prerequisites
- Git
- Node.js
- npm



### Environment Setup

Create `.env` file in the root directory:

```env
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'
```

Get your credentials from [Convex](https://www.convex.dev/) and [Clerk](https://clerk.com/).

### Run the Project

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.

## 📁 Project Structure

```
PromptCast/
├── app/                    # Next.js app directory
│   ├── (auth)/            # Authentication pages
│   ├── (root)/            # Main application pages
│   └── globals.css        # Global styles
├── components/             # Reusable components
│   ├── ui/                # ShadCN UI components
│   └── ...                # Custom components
├── convex/                # Backend functions & schema
├── lib/                   # Utility functions
├── providers/             # Context providers
├── public/                # Static assets
└── types/                 # TypeScript type definitions
```

## 🔧 Key Components

### Core Features
- **Podcast Creation**: AI-powered text-to-speech with multiple voices
- **Image Generation**: AI-generated podcast thumbnails
- **Audio Player**: Advanced playback controls with progress tracking
- **Search & Discovery**: Find podcasts by title, author, or description
- **User Profiles**: View creator profiles and their podcasts

### Technical Highlights
- **Real-time Updates**: Convex provides live data synchronization
- **File Storage**: Secure audio and image file management
- **Search Indexing**: Full-text search capabilities
- **Responsive UI**: Mobile-first design with Tailwind CSS

## 🎯 Usage

1. **Sign Up/Login**: Create an account or sign in
2. **Create Podcast**: Use the create page to generate AI podcasts
3. **Discover**: Browse trending and popular podcasts
4. **Listen**: Use the sticky player for continuous listening
5. **Manage**: View and delete your created podcasts



## 📄 License

This project is licensed under the MIT License.
