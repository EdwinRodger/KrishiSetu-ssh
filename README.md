# KrishiSetu - Symbiosis Skill Hackathon 2026

A one-stop digital platform (web + app) for farmers featuring a dedicated marketplace for crops and agri-waste, advisory resources, query support and AI based recommendations - empowering farmers with income and tools for self-reliant and sustainable rural growth.

<img width="923" height="498" alt="image" src="https://github.com/user-attachments/assets/44f55f4a-1eb6-40ed-86dc-311f61326c1d" />

## Solution Highlights 
Smart Marketplace : An easy buy-sell platform for farmers and buyers. 
Supervisor-led Query Support : Supervisors helpline and voice-chat support for farmers.
Awareness and Guidance Hub : Infographics, success stories and motivation that educate and inspire.
Multilingual Support : Hindi + English + regional languages that engages farmers.

## Techincal Features

-   **Responsive Design**: Built with Bootstrap 5 for mobile-first responsive design
-   **Modern Routing**: Uses React Router v7 for declarative routing
-   **Authentication UI**: Login and Signup pages with form validation
-   **Component-based Architecture**: Well-organized components for maintainability
-   **No Custom CSS**: Uses only Bootstrap classes for styling

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Navbar.jsx      # Navigation bar with auth buttons
│   ├── Hero.jsx        # Hero section with call-to-action
│   ├── Features.jsx    # Features showcase grid
│   ├── GetInTouch.jsx  # Contact form component
│   └── Footer.jsx      # Footer with links and info
├── pages/              # Page components
│   ├── Home.jsx        # Main landing page
│   ├── Login.jsx       # User login page
│   └── Signup.jsx      # User registration page
├── App.jsx             # Main app with routing
└── main.jsx            # Entry point with Bootstrap CSS
```

## Getting Started

1. **Install Dependencies**

    ```bash
    npm install
    ```

2. **Start Development Server**

    ```bash
    npm run dev
    ```

3. **Open Browser**
   Navigate to `http://localhost:5173` to view the application

## Technologies Used
### Languages : 
HTML CSS and JavaScript (Frontend) 
Java(Backend)
Python (Chatbot)
### Tools and Frameworks :
Flask and LangChain (RAG Chatbot)
MySQL (Database)
React (Website)
React Native (Mobile app)
React i18n (Translation)
SpringBoot (Backend)
Bootstrap (Styling)

## Key Features

### Home Page

-   Responsive navigation bar with brand and auth buttons
-   Hero section with placeholder image and call-to-action
-   Features section with 5 Bootstrap cards
-   Contact form with validation
-   Footer with links and information

### Authentication

-   Simple login/signup forms with validation
-   Toggle between guest and logged-in states
-   Form state management using React hooks

### Responsive Design

-   Mobile-first approach using Bootstrap grid
-   Responsive navigation with collapsible menu
-   Optimized for all screen sizes

## Development Notes

-   All components use functional components with hooks
-   No custom CSS - only Bootstrap classes
-   Beginner-friendly code with extensive comments
-   Form validation and state management included
-   Placeholder content for demonstration

## Future Enhancements

-   Backend integration for real authentication
-   Database connectivity for form submissions
-   Real image assets instead of placeholders
-   Advanced features like user dashboard
-   API integration for real-time data

---

Built with ❤️ for Symbiosis Skill Hackathon
