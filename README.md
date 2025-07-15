# Password Complexity Checker

A modern, real-time password complexity checker built with React, TypeScript, and Tailwind CSS. This application provides instant feedback on password strength and helps users create secure passwords that meet industry standards.

## Features

- **Real-time Password Analysis**: Instant feedback as users type their password
- **Visual Strength Indicator**: Color-coded progress bar showing password strength (Weak, Medium, Strong)
- **Detailed Requirements Checklist**: Clear indicators for each security requirement
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean, professional interface with smooth animations
- **Screenshot Capability**: Built-in screenshot functionality for demonstration
- **Export Functionality**: Download complete application as ZIP file

## Password Requirements

The application checks for the following security requirements:

- âœ“ At least 8 characters long
- âœ“ Contains uppercase letter (A-Z)
- âœ“ Contains lowercase letter (a-z)
- âœ“ Contains number (0-9)
- âœ“ Contains special character (!@#$%^&*)
- âœ“ No spaces allowed

## Technology Stack

### Frontend
- **React 18** - Modern React with hooks
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/ui** - Reusable component library
- **Lucide React** - Modern icon library
- **Wouter** - Lightweight routing
- **TanStack Query** - Data fetching and caching

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **Puppeteer** - Headless browser for screenshots
- **Archiver** - ZIP file creation
- **TypeScript** - Type-safe server code

### Build Tools
- **Vite** - Fast build tool and dev server
- **ESBuild** - JavaScript bundler
- **PostCSS** - CSS processing
- **Drizzle ORM** - Database toolkit

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd password-complexity-checker
