# AI Chat Application with Puter Authentication

A minimalist dark-themed chat interface for interacting with various AI models through Puter's AI capabilities, featuring user authentication and registration.

## Features

- Dark minimalist design with clean aesthetics
- User authentication and registration via Puter
- Support for multiple AI models:
  - Claude Sonnet 4 (default)
  - Claude Opus 4
  - GPT-4
  - GPT-3.5 Turbo
- Streaming responses for Claude models
- Fully responsive interface
- Minimalist UI with essential elements only

## Design Principles

- Dark theme with purple accent colors
- Ample whitespace (dark space)
- Minimal visual elements
- Focus on content and functionality
- Clean typography
- Subtle animations and transitions

## Authentication

This application uses Puter's built-in authentication system:

- **Sign In**: Click the "Sign In" button to authenticate with Puter
- **User Session**: The app maintains your session automatically
- **Sign Out**: Click the "Sign Out" button to end your session
- **User Info**: Displays your username when signed in

Puter handles all authentication securely and automatically creates temporary users if needed.

## How to Use

1. Open `index.html` in a web browser
2. Click "Sign In" to authenticate with Puter
3. Select your preferred AI model from the dropdown
4. Type your message in the input field at the bottom
5. Press Enter or click "Send" to submit
6. View the AI response in the chat area

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses Puter.js SDK for AI integration and authentication
- No external dependencies
- CSS variables for consistent theming
- Flexbox layout for responsive design
- Implements Puter's authentication API:
  - `puter.auth.signIn()`
  - `puter.auth.signOut()`
  - `puter.auth.isSignedIn()`
  - `puter.auth.getUser()`

## Project Structure

```
├── index.html          # Main application file
├── server.js           # Local development server
├── package.json        # Project metadata and scripts
├── README.md           # This file
└── 404.html            # Error page
```

## Running Locally

1. Clone or download this repository
2. Run `npm start` or `node server.js`
3. Open http://localhost:3000 in your browser

## Deployment

This application can be deployed to any static hosting service:

1. GitHub Pages
2. Netlify
3. Vercel
4. Any standard web server

Simply upload all files to your hosting provider.

## API Integration

This application integrates with Puter's AI services:

- **AI Chat**: `puter.ai.chat()` for conversational AI
- **Authentication**: `puter.auth.*` for user management
- **Models**: Supports multiple AI models including Claude Sonnet 4

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Requirements

- Modern web browser
- Internet connection for API access

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a pull request

## License

This project is licensed under the MIT License.

## Powered by Puter

This application uses Puter's web operating system and AI capabilities. Learn more at [https://developer.puter.com](https://developer.puter.com)