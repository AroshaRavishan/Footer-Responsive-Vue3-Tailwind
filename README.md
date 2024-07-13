# Footer Component

## Overview
This component is a comprehensive footer designed for a Vue.js application. It provides a rich set of features including social media links, quick navigation, resource links, and customization options.

## Features

### 1. Dynamic Year Display
- Automatically updates the copyright year.

### 2. Responsive Design
- Adapts to different screen sizes with tailored layouts for mobile and desktop views.

### 3. Social Media Integration
- Includes buttons for Facebook, Instagram, Twitter, LinkedIn, and YouTube.
- Each button has hover effects and uses SVG icons.

### 4. Quick Links Section
- Provides easy navigation to key areas of the website.

### 5. Resources Sections
- Two separate resource sections with multiple links for extensive site navigation.

### 6. Currency Selection
- Allows users to choose their preferred currency.
- Options include GBP, CAD, USD, EURO, INR, and AED.
- Selected currency is stored in local storage for persistence across sessions.

### 7. Language Selection (UI Prepared, Functionality To Be Implemented)
- Dropdown for selecting the preferred language.
- Includes options for English, Spanish, French, German, and Italian.

### 8. Certificate Verification
- Button for users to verify their certificates.

### 9. Contact Information
- Displays contact details including phone numbers and email.

### 10. Legal Information
- Copyright notice with dynamically updated year.
- Links to Privacy Policy, Terms of Service, and Cookie Policy.

## Technical Details

### Vue.js Integration
- Utilizes Vue 3 Composition API with `<script setup>`.
- Uses `ref`, `defineProps`, `onMounted`, and `watch` from Vue.

### Inertia.js Integration
- Implements `Link` component from Inertia.js for internal navigation.
- Uses `usePage` to access shared props.

### Local Storage Usage
- Stores and retrieves user's currency preference.

### Reactivity
- Implements reactive components for currency and language selection.

### Custom Styling
- Uses Tailwind CSS classes for styling.
- Includes custom media queries for responsive design.

## Implementation Notes
- The component is designed to be easily integrated into a larger Vue.js application.
- Some functionalities (like language application) are prepared in the UI but require backend implementation.
- The design follows modern web practices with a focus on user experience and accessibility.

## Future Enhancements
- Complete implementation of language selection functionality.
- Potential for adding more customization options.
- Possibility to expand social media integrations.

This footer component provides a solid foundation for website navigation, user preferences, and brand representation, making it a valuable addition to any Vue.js based web application.
