# Reverse Engineering Labs Hub

A systematic study of complex frontend systems for deeper understanding of system design and architecture patterns.

## Project Overview

This repository contains reverse engineering studies of popular web platforms from a frontend developer's perspective. Each study includes:

1. **System Analysis**: Detailed documentation of the system design
2. **Architecture Diagrams**: Visual representations using Mermaid.js
3. **Implementation**: Simplified version of the platform using modern frontend technologies

## Methodology

For each platform, the following approach is taken:

1. **Observation**: Analyzing the user interface, interactions, and behaviors
2. **Component Breakdown**: Identifying key components and their relationships
3. **State Management Analysis**: Understanding how data flows through the application
4. **Performance Considerations**: Noting optimization techniques used
5. **Implementation**: Creating a simplified version with similar architecture

## Technologies Used

All implementations use the following technologies:

- **Frontend**: React + TypeScript
- **Styling**: TailwindCSS
- **State Management**: Redux Toolkit, RTK Query, React Context
- **Backend**: Firebase (BaaS)
- **Code Quality**: ESLint, Prettier
- **Performance**: Skeleton screens, optimistic loading

## Platforms (From Simplest to Most Complex)

1. **CKE Editor** (Text Editing Platform)
2. **Spotify** (Media Player Platform)
3. **Notion** (Advanced Text Writing Platform)
4. **Gmail** (Mail Client)
5. **Udemy** (Learning Management System)
6. **Meta** (Social Media Platform)
7. **Netflix** (Video Streaming Platform)
8. **Allegro/Amazon** (E-commerce Platform)
9. **Google Maps** (Maps)
10. **Figma** (Collaborative Design Tool)
11. **Interactive Brokers** (Real-time Financial Platform)
12. **Visual Studio Code** (Advanced Code Editor)

## Project Structure

```
/
├── README.md
├── platforms/
│   ├── cke-editor/
│   ├── spotify/
│   ├── notion/
│   └── ...
└── shared/
    ├── components/
    ├── hooks/
    └── utils/
```

## Getting Started

1. Choose a platform directory to explore
2. Read the system analysis document
3. Review the architecture diagrams
4. Explore the implementation code
5. Run the implementation locally following the README in each platform directory

## Global Linting Configuration

This project uses a global linting configuration approach:

1. **Root Configuration Files**:
   - `.editorconfig`: Defines consistent coding styles across different editors and IDEs
   - `.eslintrc.js`: JavaScript and TypeScript linting rules
   - `.prettierrc`: Code formatting rules

2. **Platform-Specific Extensions**:
   - Each platform extends the root configuration
   - Platform-specific overrides can be added when necessary
   - This ensures consistency while allowing for flexibility

3. **Creating New Platforms**:
   - Use the `scripts/create-platform.mjs` script to create new platforms
   - This automatically sets up the correct linting configuration inheritance

## Contributing

This is a personal learning project, but suggestions and improvements are welcome!
