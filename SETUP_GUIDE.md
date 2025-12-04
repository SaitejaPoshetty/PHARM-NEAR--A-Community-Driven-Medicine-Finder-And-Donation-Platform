# Pharm Near - Complete Setup Guide for VS Code

## Quick Start (5 minutes)

### 1. Prerequisites Check
\`\`\`bash
# Check Node.js version (should be v18+)
node --version

# Check npm version
npm --version
\`\`\`

### 2. Install & Run
\`\`\`bash
# Install dependencies
npm install

# Start development server
npm run dev
\`\`\`

### 3. Open in Browser
Visit: **http://localhost:3000**

---

## Detailed Setup Instructions

### For Windows Users

1. **Install Node.js**
   - Download from https://nodejs.org/
   - Run the installer and follow the prompts
   - Restart your computer

2. **Open VS Code**
   - Download from https://code.visualstudio.com/
   - Install and open it

3. **Open Project Folder**
   - File → Open Folder
   - Select the pharm-near project folder

4. **Open Terminal in VS Code**
   - Press `Ctrl + ` (backtick)
   - Or go to Terminal → New Terminal

5. **Install Dependencies**
   \`\`\`bash
   npm install
   \`\`\`

6. **Start Development Server**
   \`\`\`bash
   npm run dev
   \`\`\`

7. **Open in Browser**
   - Click the link in terminal or visit http://localhost:3000

### For Mac Users

1. **Install Node.js**
   \`\`\`bash
   # Using Homebrew (recommended)
   brew install node
   
   # Or download from https://nodejs.org/
   \`\`\`

2. **Open VS Code**
   - Download from https://code.visualstudio.com/
   - Install and open it

3. **Open Project Folder**
   - File → Open
   - Select the pharm-near project folder

4. **Open Terminal in VS Code**
   - Press `Cmd + ` (backtick)
   - Or go to Terminal → New Terminal

5. **Install Dependencies**
   \`\`\`bash
   npm install
   \`\`\`

6. **Start Development Server**
   \`\`\`bash
   npm run dev
   \`\`\`

7. **Open in Browser**
   - Click the link in terminal or visit http://localhost:3000

### For Linux Users

1. **Install Node.js**
   \`\`\`bash
   # Ubuntu/Debian
   sudo apt update
   sudo apt install nodejs npm
   
   # Or download from https://nodejs.org/
   \`\`\`

2. **Open VS Code**
   \`\`\`bash
   # Install VS Code
   sudo snap install code --classic
   
   # Or download from https://code.visualstudio.com/
   \`\`\`

3. **Open Project Folder**
   - File → Open Folder
   - Select the pharm-near project folder

4. **Open Terminal in VS Code**
   - Press `Ctrl + ` (backtick)
   - Or go to Terminal → New Terminal

5. **Install Dependencies**
   \`\`\`bash
   npm install
   \`\`\`

6. **Start Development Server**
   \`\`\`bash
   npm run dev
   \`\`\`

7. **Open in Browser**
   - Click the link in terminal or visit http://localhost:3000

---

## Testing the Application

### Demo Login
- **Email**: sarah@example.com
- **Password**: password

### Create New Account
1. Click "Sign Up"
2. Choose a role (Patient, Donor, Pharmacy, or NGO)
3. Fill in the form
4. Click "Sign Up"

### Features to Test

**Search Medicines**
- Go to "Search Medicines" tab
- Search for any medicine name
- Filter by type (Donation/Sale)
- Click on results to see details

**Create Listing**
- Go to "My Listings" tab
- Click "Create New Listing"
- Fill in medicine details
- Click "Create Listing"

**Send Messages**
- Go to "Messages" tab
- Click "New Message"
- Select a user and send a message

**Update Profile**
- Go to "Profile" tab
- Update your information
- Click "Save Changes"

---

## Common Issues & Solutions

### Issue: "npm: command not found"
**Solution**: Node.js is not installed. Download and install from https://nodejs.org/

### Issue: Port 3000 already in use
**Solution**: 
\`\`\`bash
npm run dev -- -p 3001
\`\`\`

### Issue: Module not found errors
**Solution**:
\`\`\`bash
# Clear cache and reinstall
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
\`\`\`

### Issue: Slow performance
**Solution**:
- Close other applications
- Clear browser cache (Ctrl+Shift+Delete)
- Restart the development server

### Issue: Changes not reflecting
**Solution**:
- Hard refresh browser (Ctrl+Shift+R or Cmd+Shift+R)
- Restart development server (Ctrl+C, then npm run dev)

---

## VS Code Extensions (Recommended)

Install these extensions for better development experience:

1. **ES7+ React/Redux/React-Native snippets**
   - Search: "ES7+ React/Redux/React-Native snippets"
   - By dsznajder.es7-react-js-snippets

2. **Tailwind CSS IntelliSense**
   - Search: "Tailwind CSS IntelliSense"
   - By bradlc.vscode-tailwindcss

3. **TypeScript Vue Plugin**
   - Search: "TypeScript Vue Plugin"
   - By Vue

4. **Prettier - Code formatter**
   - Search: "Prettier"
   - By Prettier

5. **Thunder Client** (for API testing)
   - Search: "Thunder Client"
   - By Rangav

---

## Next Steps

1. **Explore the Code**
   - Open `app/page.tsx` to see the main page
   - Check `components/dashboard.tsx` for the dashboard layout
   - Review `lib/auth-context.tsx` for authentication logic

2. **Customize the App**
   - Update colors in `app/globals.css`
   - Modify components in `components/` folder
   - Add new features as needed

3. **Deploy (Optional)**
   - Build for production: `npm run build`
   - Deploy to Vercel, Netlify, or your hosting provider

---

## Need Help?

- Check the main README.md for more information
- Review the code comments for explanations
- Check browser console (F12) for error messages
- Search for solutions online

**Happy coding! 🚀**
