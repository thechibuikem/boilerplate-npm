# FreeCodeCamp NPM Package Management Project

## Overview
This is a Node.js Express application from FreeCodeCamp's backend challenges, specifically designed to teach managing NPM packages and package.json configuration.

## Project Architecture
- **Backend**: Express.js server serving static files and API endpoints
- **Frontend**: Simple HTML page with CSS styling
- **Port**: Configured to run on port 5000 for Replit environment
- **Host**: Bound to 0.0.0.0 to work with Replit's proxy system

## Key Features
- Serves static HTML content from `/views/index.html`
- Provides API endpoint at `/_api/package.json` that returns package.json content
- Static file serving from `/public` directory
- CORS configuration for specific origins

## Recent Changes
- 2025-09-29: Configured for Replit environment
  - Updated server to bind to 0.0.0.0:5000
  - Set up workflow for automatic startup
  - Configured deployment for autoscale production hosting

## Current State
- Dependencies installed and working
- Server running successfully on port 5000
- All endpoints tested and functional
- Ready for deployment to production