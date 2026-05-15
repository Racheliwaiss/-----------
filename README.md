# LIZI - Music Collaboration Platform

A modern web-based music platform empowering amateur musicians to create, collaborate, discover, and share their music with a vibrant community.

## Overview

LIZI is a comprehensive music ecosystem designed to democratize music creation and distribution. Whether you're an aspiring producer, hobbyist musician, or music curator, LIZI provides intuitive tools and a supportive community to bring your musical vision to life.

## Key Features

- **Music Studio**: Browser-based music creation and editing tools
- **Discovery Hub**: Browse and discover music from other amateur musicians
- **User Profiles**: Showcase your portfolio with statistics and follower systems
- **Collaboration Tools**: Connect with other musicians for remixes and projects
- **Community Engagement**: Comments, likes, playlists, and sharing capabilities

## Target Audience

- **Aspiring Producers** (Ages 16-35): Learning production independently, seeking feedback and exposure
- **Hobbyist Musicians**: Creating music for leisure with an easy-to-use platform
- **Collaborators**: Partners looking to work on remixes and projects together
- **Music Curators**: Discovering and sharing music with their network

## Tech Stack

- **Frontend**: React 18
- **Build Tool**: Vite
- **Styling**: Custom design system with dark theme
- **Linting**: ESLint with React support
- **Package Manager**: npm

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd lizi
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173` (default Vite port).

## Development

### Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

### Project Structure

```
src/
├── components/     # Reusable React components
├── pages/          # Page components
├── styles/         # Global styles and design system
└── utils/          # Utility functions and helpers

Public assets:
├── index.html      # Main entry point
├── login.html      # Authentication page
├── profile.html    # User profile page
├── search.html     - Music search and discovery
├── messages.html   # Messaging interface
└── collaboration.html  # Collaboration features
```

## Design System

LIZI uses a modern dark theme with carefully crafted color palette:

- **Primary Color**: White (#ffffff)
- **Surface Colors**: Dark grays (#131313 - #353534)
- **Text Color**: Light beige (#e5e2e1)
- **Accent Color**: Light gray (#c8c6c5)

For detailed design specifications, see [DESIGN.md](DESIGN.md)

## Documentation

- [PRD.md](PRD.md) - Complete Product Requirements Document
- [DESIGN.md](DESIGN.md) - Design system and visual specifications
- [COMPONENTS_README.md](COMPONENTS_README.md) - Component documentation

## Contributing

We welcome contributions! Please ensure your code:
- Follows the ESLint rules configured in the project
- Maintains the design system specifications
- Includes appropriate documentation

## Project Status

**Current Version**: 1.0.0  
**Status**: In Development  
**Last Updated**: May 2026

## License

[Add your license information here]

## Support

For questions, feedback, or issues, please reach out to the development team.

---

**Built with ❤️ for musicians everywhere**
