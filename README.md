# Snap Cares

<div align="center">
  <img src="./assets/better_youth_logo.png" alt="Better Youth Logo" width="200">
  
  <p>A Snapchat feature enabling foster youth nonprofits to expand their social media presence through community profiles, real-time chat, and resource discovery. Built in partnership with Better Youth during the Snapchat Software Engineering Academy.</p>

  <p>
    <a href="#features">Features</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#installation">Installation</a> •
  </p>
</div>

---

## About The Project

Snap Cares is a Snapchat feature designed to empower foster youth nonprofits by expanding their social media presence and community engagement capabilities. Developed by a team of 3 engineers working on frontend and backend systems to create a comprehensive mobile feature.

The project was developed through collaboration with:
- **3 Engineers** for full-stack development
- **2 Designers** for UI/UX design
- **2 Marketers** for user research and feature optimization
- **Better Youth** as our nonprofit partner

### Project Impact

This feature enables nonprofits like Better Youth to:
- Build and maintain community profiles with rich content
- Connect with foster youth through real-time group chat
- Share resources and event information effectively
- Expand their digital presence on a platform youth already use

The final product was delivered at a **company showcase**, presented to executives and over **200+ attendees**, demonstrating the potential of technology to create meaningful social impact.

### Mission Alignment

Better Youth's mission is to bridge resource gaps and prepare foster and system-impacted youth for success in the creative economy. Snap Cares supports this mission by providing a centralized platform for community engagement, resource access, and peer-to-peer connection.

---

## Features

### 🌐 Nonprofit Community Profiles
- **Frontend community profile pages** with rich content display
- Organization profiles with follower tracking and member engagement
- "Ask a Question" feature for direct community interaction
- Stories, Spotlight, and Places sections for content discovery
- Profile verification badges and metadata display

### 💬 Real-Time Group Chat System
- **Real-time messaging functionality** using Supabase
- Group chat capabilities for community discussions
- Friend connections and private messaging
- Integrated chat interface using React Native Gifted Chat
- Real-time message synchronization across devices

### 🗄️ Backend Database Architecture
- **Supabase backend** powering all features
- PostgreSQL database schema for events, organizations, and user data
- Real-time subscriptions for chat and content updates
- Secure authentication and user management
- RESTful API integration across the mobile app

### 🗺️ Interactive Resource Map
- Map view of LA County foster youth organizations
- Location-based resource discovery
- GPS integration for finding nearby services
- Organization markers with detailed information

---

## Tech Stack

### Frontend
- **React Native** - Cross-platform mobile development
- **Expo** - Development platform and tooling
- **React Navigation** - Navigation and routing

### Backend & Services
- **Supabase** - Backend as a Service (BaaS)
  - PostgreSQL database
  - Real-time subscriptions
  - Authentication
  - Storage

---

## Installation

### Prerequisites

Ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator (for Mac) or Android Studio (for Android development)

```bash
# Install Expo CLI globally
npm install -g expo-cli
```

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/AlejandroLarson/2025-Snap-FosterYouth.git
   cd 2025-Snap-FosterYouth
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure Supabase**
   
   Create a `.env` file in the root directory:
   ```env
   EXPO_PUBLIC_SUPABASE_URL=your_supabase_url
   EXPO_PUBLIC_SUPABASE_KEY=your_supabase_anon_key
   ```

   Get your Supabase credentials from your [Supabase project dashboard](https://supabase.com/dashboard).

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Run on your device**
   - Scan the QR code with the Expo Go app (iOS/Android)
   - Or press `i` for iOS simulator
   - Or press `a` for Android emulator

---

## Usage

### Running the App

```bash
# Start Expo development server
npm start

# Run on iOS
npm run ios

# Run on Android
npm run android

# Run on web
npm run web
```

### Main Navigation

The app features a bottom tab navigation with the following screens:
- **Home** - Main feed and community updates
- **Chat** - Messaging and conversations
- **Camera** - Capture and share moments
- **Map** - Find nearby resources and organizations
- **Events** - Discover and manage community events

### Key User Flows

1. **Joining a Community**
   - Navigate to the Better Youth community page
   - Tap "Join Community" to connect with others

2. **Discovering Resources**
   - Open the Map screen
   - View organizations across LA County
   - Tap markers for detailed information

---

## Development Context

This project was developed as part of the **Snapchat Software Engineering Academy**, with a focus on creating technology solutions for social impact. 

---

## Team & Collaboration

This project was built through cross-functional collaboration:

### Engineering Team (3)
- Full-stack development across frontend and backend
- Feature implementation and system integration

### Design Team (2)
- UI/UX design for community profiles and chat interfaces
- User experience optimization and design systems

### Marketing Team (2)
- User research and needs assessment
- Feature optimization and user testing

### Nonprofit Partner
- **Better Youth** - Requirements gathering, user feedback, and mission alignment

---

## License

This project was created as part of the Snapchat Software Engineering Academy.
