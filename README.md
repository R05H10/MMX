# 🎬 Decentralized Netflix

A blockchain-powered streaming platform built with React and Web3 technologies, offering a decentralized alternative to traditional streaming services.


<img width="997" height="417" alt="image" src="https://github.com/user-attachments/assets/3e3a5a2b-521d-47d7-8058-3c890b3f6d80" />

## 🌟 Overview


Decentralized Netflix is a modern web application that leverages blockchain technology to create a decentralized streaming platform. Users can connect their Web3 wallets, browse movies, and manage their personal movie lists in a secure, decentralized environment.

## Workflow 
```mermaid
flowchart TD
    A[User opens the Decentralized App]
    A --> B1[Connects Web3 Wallet]
    A --> B2[Authentication via Moralis]

    B1 --> C1[Login with Wallet]
    B2 --> C2[Fetch User Data]
    C1 --> C3[Display Movie List]
    C2 --> C3

    C3 --> D1[User Selects a Movie]
    C3 --> D2[Stream Movie via Player]
    D1 --> E[Log Activity to Moralis]
    D2 --> E

    E --> F1[Update Watchlist on Web3]
    E --> F2[Experience is Private & Decentralized]
```





## Demo




https://github.com/user-attachments/assets/824cc196-4fb4-49e3-9724-6e55dc589062






## ✨ Features

- **🔐 Web3 Authentication**: Connect with MetaMask and other Web3 wallets
- **🎥 Movie Streaming**: Browse and watch movies in a Netflix-like interface
- **📱 Responsive Design**: Optimized for desktop and mobile devices
- **🗂️ Personal Movie Lists**: Save and manage your favorite movies
- **⚡ Moralis Integration**: Powered by Moralis for blockchain interactions
- **🎨 Modern UI**: Clean, intuitive interface with Ant Design components

## 🛠️ Technology Stack

- **Frontend**: React 17, React Router DOM 6
- **Blockchain**: Moralis, Web3UIKit
- **Styling**: CSS3, Ant Design
- **Build Tool**: Create React App
- **Testing**: Jest, React Testing Library

## 📋 Prerequisites

Before running this project, make sure you have:

- Node.js (version 14 or higher)
- npm or yarn package manager
- A Web3 wallet (MetaMask recommended)
- Moralis account (for backend services)

## 🚀 Getting Started

### 1. Clone the Repository

```bash

cd Decentralized-Netflix
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Environment Setup

Create a `.env` file in the root directory and add your Moralis configuration:

```env
REACT_APP_MORALIS_SERVER_URL=your_moralis_server_url
REACT_APP_MORALIS_APP_ID=your_moralis_app_id
```

### 4. Start the Development Server

```bash
npm start
```

The application will open in your browser at `http://localhost:3000`.

## 📁 Project Structure

```
src/
├── components/           # Reusable React components
├── pages/               # Main application pages
│   ├── Home.js         # Homepage with movie listings
│   └── Player.js       # Video player interface
├── helpers/            # Utility functions and data
│   └── library.js      # Movie data and configurations
├── images/             # Static assets and movie thumbnails
└── App.js              # Main application component
```

## 🎯 Key Components

### Home Page (`src/pages/Home.js`)
- Displays movie collections and categories
- Handles Web3 wallet connections
- Manages user's personal movie list
- Integrates with Moralis cloud functions

### Player Page (`src/pages/Player.js`)
- Video streaming interface
- Movie details and metadata
- Responsive video player controls

### Movie Library (`src/helpers/library.js`)
- Centralized movie data management
- Movie metadata and thumbnails
- Category and genre classifications

## 🔧 Available Scripts

- `npm start` - Start development server
- `npm build` - Build for production
- `npm test` - Run test suite
- `npm eject` - Eject from Create React App (⚠️ irreversible)

## 🌐 Web3 Integration

This project integrates with the Web3 ecosystem through:

- **Moralis**: Backend-as-a-Service for Web3 applications
- **Web3UIKit**: Pre-built Web3 UI components
- **Wallet Connection**: Support for MetaMask and other Web3 wallets
- **Blockchain Data**: Decentralized storage and user management

## 🎨 UI/UX Features

- Netflix-inspired design language
- Smooth animations and transitions
- Mobile-responsive layout
- Dark theme optimized for streaming
- Intuitive navigation and user flow

## 🔐 Security & Privacy

- No central data storage
- Wallet-based authentication
- Decentralized user data management
- Secure Web3 transactions

## 🤝 Contributing

We welcome contributions! 

