# EchoPark Vue.js Prototype

This is the Vue.js version of the EchoPark prototype, rebuilt from the original HTML pages.

## Project Structure

```
prototype2/
├── src/
│   ├── components/
│   │   ├── Navigation.vue       # Main navigation component
│   │   └── HamburgerMenu.vue    # Hamburger menu drawer
│   ├── views/
│   │   ├── Homepage.vue         # Homepage with hero section
│   │   ├── SavedSearches.vue    # Saved searches list page
│   │   └── SearchResults.vue    # Search results page (SRP)
│   ├── router/
│   │   └── index.js            # Vue Router configuration
│   ├── App.vue                 # Root component
│   ├── main.js                 # Application entry point
│   └── style.css               # Global styles
├── index-vue.html              # Main HTML entry point
├── package.json                # Dependencies
├── vite.config.js              # Vite configuration
└── Illustrations/              # All image assets (unchanged)
```

## Getting Started

### Installation

1. Install dependencies:
```bash
npm install
```

### Development

Run the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

### Build

Build for production:
```bash
npm run build
```

### Preview

Preview production build:
```bash
npm run preview
```

## Pages

- **Homepage** (`/homepage`) - EchoPark homepage with hero section, shop categories, and company introduction
- **Saved Searches** (`/saved-searches`) - List of saved searches with search functionality
- **Search Results** (`/search`) - Search results page with filters, filter menu, and vehicle listings

## Features

- ✅ Vue 3 Composition API (Options API used for compatibility)
- ✅ Vue Router for navigation
- ✅ Responsive mobile-first design
- ✅ Hamburger menu with slide-in animation
- ✅ Filter menu with tabs (Filters / My Searches)
- ✅ Saved search functionality with localStorage
- ✅ Name search modal
- ✅ Filter pills system
- ✅ Vehicle listing tiles
- ✅ Favorite functionality

## Components

### Navigation
Reusable navigation component with hamburger menu, logo, location, and search bar.

### HamburgerMenu
Slide-in menu drawer with primary and secondary navigation links.

### Views
- **Homepage**: Hero section, shop categories, company introduction cards
- **SavedSearches**: Searchable list of saved searches
- **SearchResults**: Complete search results page with filtering, saved searches, and vehicle listings

## Data Persistence

The application uses `localStorage` to persist:
- Saved searches
- Sign-in status
- Selected search criteria

## Asset Paths

All image assets are referenced from the `Illustrations/` directory, maintaining the same structure as the original HTML prototype.

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- The Vue version maintains the same visual design and functionality as the original HTML prototype
- All interactive features are implemented using Vue.js reactive data and computed properties
- The component structure allows for easy maintenance and extension

