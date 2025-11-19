# Prototype 1.1 - EchoPark Saved Search

This is the base prototype for EchoPark's saved search functionality usability testing.

## Overview

A mobile prototype simulating the EchoPark mobile experience for saved search functionality, including:

- **Homepage**: EchoPark mobile homepage with navigation and search
- **Search Results Page (SRP)**: Vehicle listings with filtering and saved search capabilities
- **Filter System**: Body style, price range, and other filter options
- **Saved Searches**: User can save, name, and manage their search criteria
- **Sign-in Flow**: Account creation and sign-in modals
- **Toast Notifications**: Various user feedback messages

## Features

### Filter System
- Body style selection with multi-select capability
- Price range slider with dual-thumb controls
- Distance & store selection
- Filter pills that appear when selections are made
- Reset functionality to clear all filters

### Saved Search Management
- Save current search criteria
- Name custom searches
- View all saved searches in "My searches" tab
- Apply saved searches to current filters
- Radio button selection (only one active at a time)

### User Authentication
- Sign-in modal with form validation
- Account creation flow
- State management for signed-in users
- Different UI states based on authentication status

### Interactive Elements
- Hamburger menu with slide-in animation
- Filter menu with tab switching
- Toast notifications for user feedback
- Vehicle tiles with favorite functionality
- Responsive mobile design (375px viewport)

## Technical Details

- `homepage.html` - EchoPark mobile homepage
- `search-not-saved.html` - Main search results page with all functionality
- `Illustrations/` - All visual assets organized by category

## Usage

1. Open `homepage.html` to start the prototype
2. Navigate through the mobile interface
3. Test the saved search functionality
4. Use the filter system to refine results
5. Sign in to access saved search management

## Testing Scenarios

This prototype supports various usability testing scenarios including:
- First-time user experience
- Returning user with saved searches
- Filter interaction and persistence
- Account creation and sign-in flows
- Search management and organization

## Deployment

This prototype is designed to be deployed on Vercel or any static hosting service.