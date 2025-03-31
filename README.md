# URL Shortener

## Project Overview
This is a client-side URL shortening application built with React and TypeScript that allows users to create and manage shortened URLs using browser local storage.

## Prerequisites
- Node.js & npm installed (recommend using nvm for installation)
- Basic knowledge of React and TypeScript
- Git for version control (optional, but recommended)

## Technology Stack
- **Frontend Framework**: React 18.3.1 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Component Library**: shadcn/ui (built on Radix UI)
- **Icons**: Lucide React
- **Routing**: react-router-dom
- **State Management**: React hooks + localStorage

### Additional Libraries
- `react-qr-code` for QR code generation
- `sonner` for toast notifications
- `@tanstack/react-query` (minimally used)

## Project Structure
- **Pages**: Index, About, RedirectPage, NotFound
- **Components**: Header, UrlShortener, and UI components
- **Hooks**: Custom React hooks
- **Utilities**: Helper functions

## Key Features
- URL shortening with client-side code generation
- History of recently shortened URLs (max 5)
- Copy-to-clipboard functionality
- QR code generation for each shortened URL
- Client-side redirection system
- Responsive design for all device sizes

## Deployment Options
### 1. Lovable Default Deployment
1. Open the project in Lovable
2. Click on **Share -> Publish**
3. The application will be deployed to a Lovable subdomain

### 2. Custom Domain via Netlify
1. Export the project from Lovable
2. Create a Netlify account if you don't have one
3. Connect your repository to Netlify
4. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
5. Set up your custom domain in Netlify settings

### 3. Local Development
```sh
# Clone the repository
git clone <repository-url>

# Navigate to project directory
cd url-shortener

# Install dependencies
npm install

# Start development server
npm run dev
```

## Technical Limitations
- Client-side only (uses localStorage)
- URLs are only available on the device where they were created
- No analytics or click tracking
- No user accounts or authentication

## Future Enhancement Possibilities
- Server-side implementation for persistent storage
- User accounts and authentication
- Analytics dashboard for tracking link usage
- Custom short codes instead of random generation
- Link expiration options

## Browser Compatibility
- Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- Requires localStorage support
- Responsive design for mobile and desktop


