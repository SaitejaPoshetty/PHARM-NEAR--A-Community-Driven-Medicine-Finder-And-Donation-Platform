# Pharm Near - Medicine Accessibility Platform

A web-based platform that helps people find nearby pharmacies or individuals willing to donate extra or unused medicines. Built with Next.js, React, and Tailwind CSS.

## Features

- **User Authentication**: Sign up as Patient, Donor, Pharmacy, or NGO
- **Medicine Search**: Location-based search with real-time filtering
- **Listings Management**: Create and manage medicine listings
- **Messaging System**: Direct communication between users
- **User Profiles**: Complete profile management with verification
- **Responsive Design**: Works seamlessly on desktop and mobile

## Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v18 or higher) - [Download](https://nodejs.org/)
- **npm** or **yarn** or **pnpm** (comes with Node.js)
- **Git** (optional, for cloning)
- **VS Code** (optional, recommended editor)

## Installation & Setup

### Step 1: Clone or Download the Project

**Option A: Using Git**
\`\`\`bash
git clone <repository-url>
cd pharm-near
\`\`\`

**Option B: Download ZIP**
- Download the project ZIP file
- Extract it to your desired location
- Open the folder in VS Code

### Step 2: Install Dependencies

Open a terminal in the project directory and run:

\`\`\`bash
npm install
\`\`\`

Or if you prefer yarn:
\`\`\`bash
yarn install
\`\`\`

Or if you prefer pnpm:
\`\`\`bash
pnpm install
\`\`\`

### Step 3: Set Up Environment Variables

Create a `.env.local` file in the root directory (copy from `.env.example`):

\`\`\`bash
cp .env.example .env.local
\`\`\`

The `.env.local` file is already configured with default values. No additional setup is needed for local development.

### Step 4: Run the Development Server

\`\`\`bash
npm run dev
\`\`\`

Or with yarn:
\`\`\`bash
yarn dev
\`\`\`

Or with pnpm:
\`\`\`bash
pnpm dev
\`\`\`

The application will start at **http://localhost:3000**

## Usage

### First Time Setup

1. Open http://localhost:3000 in your browser
2. Click "Sign Up" to create an account
3. Choose your user role:
   - **Patient**: Looking for medicines
   - **Donor**: Willing to donate medicines
   - **Pharmacy**: Operating a pharmacy
   - **NGO**: Non-profit organization

### Demo Credentials

You can also log in with demo credentials:
- **Email**: sarah@example.com
- **Password**: password

### Main Features

**Search Medicines**
- Use the search tab to find medicines by name
- Filter by type (Donation/Sale)
- View results with distance and availability

**Create Listings**
- Add medicines you want to donate or sell
- Include expiry date, quantity, and description
- Set location for local discovery

**Messaging**
- Send direct messages to other users
- Negotiate prices or donation terms
- Track conversation history

**User Profile**
- Update your information
- Set your location
- View your verification status

## Project Structure

\`\`\`
pharm-near/
├── app/
│   ├── layout.tsx          # Root layout with providers
│   ├── page.tsx            # Main page (landing/dashboard)
│   └── globals.css         # Global styles
├── components/
│   ├── auth/               # Authentication components
│   ├── ui/                 # Reusable UI components
│   ├── dashboard.tsx       # Main dashboard
│   ├── search-medicines.tsx
│   ├── my-listings.tsx
│   ├── messages.tsx
│   └── user-profile.tsx
├── lib/
│   ├── auth-context.tsx    # Authentication context
│   ├── data-context.tsx    # Data management context
│   ├── mock-data.ts        # Sample data
│   ├── types.ts            # TypeScript types
│   └── utils.ts            # Utility functions
├── public/                 # Static assets
├── package.json            # Dependencies
├── tsconfig.json           # TypeScript config
├── next.config.mjs         # Next.js config
└── tailwind.config.ts      # Tailwind CSS config
\`\`\`

## Available Scripts

\`\`\`bash
# Development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linter
npm run lint
\`\`\`

## Technologies Used

- **Next.js 15** - React framework
- **React 19** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS 4** - Styling
- **Shadcn/ui** - Component library
- **React Hook Form** - Form management
- **Zod** - Schema validation
- **Lucide React** - Icons

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Troubleshooting

### Port 3000 Already in Use

If port 3000 is already in use, you can specify a different port:

\`\`\`bash
npm run dev -- -p 3001
\`\`\`

### Dependencies Installation Issues

Clear npm cache and reinstall:

\`\`\`bash
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
\`\`\`

### Build Errors

Make sure you're using Node.js v18 or higher:

\`\`\`bash
node --version
\`\`\`

## Development Tips

- **Hot Reload**: Changes to files are automatically reflected in the browser
- **Console Logs**: Open browser DevTools (F12) to see console output
- **React DevTools**: Install React DevTools browser extension for debugging
- **TypeScript**: Errors will show in the terminal and VS Code

## Future Enhancements

- Real database integration (Supabase/Firebase)
- Google Maps integration for real location tracking
- Payment integration for medicine purchases
- Email notifications
- Admin dashboard for moderation
- Medicine verification system
- Rating and review system

## License

This project is open source and available under the MIT License.

## Support

For issues or questions, please open an issue in the repository or contact the development team.

---

**Happy coding! 🚀**
