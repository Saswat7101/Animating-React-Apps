# React Challenges

A beautiful React application for managing and tracking personal challenges with smooth animations. Built with React, Vite, and Framer Motion.

## Features

- **Challenge Management**: Create, view, and manage your personal challenges
- **Smooth Animations**: Beautiful transitions and animations using Framer Motion
- **Tab-based Navigation**: Filter challenges by status (Active, Completed, All)
- **Modal System**: Interactive modal for creating new challenges
- **Responsive Design**: Works on desktop and mobile devices

## Tech Stack

- **React** 19 - UI library
- **Vite** - Build tool and development server
- **Framer Motion** - Animation library
- **React Router DOM** - Client-side routing

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```
bash
git clone <repository-url>
```

2. Navigate to the project directory:

```
bash
cd animating-react-apps
```

3. Install dependencies:

```
bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Build

Create a production build:

```
bash
npm run build
```

### Preview

Preview the production build:

```
bash
npm run preview
```

## Project Structure

```
src/
├── assets/          # Static assets (images)
├── components/     # Reusable React components
│   ├── Badge.jsx
│   ├── ChallengeItem.jsx
│   ├── Challenges.jsx
│   ├── ChallengeTabs.jsx
│   ├── Header.jsx
│   ├── Modal.jsx
│   └── NewChallenge.jsx
├── pages/          # Page components
│   ├── Challenges.jsx
│   └── Welcome.jsx
├── store/          # State management
│   └── challenges-context.jsx
├── App.jsx         # Main app component
├── main.jsx        # Entry point
└── index.css       # Global styles
```

## Routes

- `/` - Welcome page
- `/challenges` - Challenges management page

## License

MIT
