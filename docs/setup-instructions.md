# 🚀 Debaite Setup Instructions for Akshara

Hi Akshara! 👋 Follow these simple steps to get the Debaite project running on your computer.

## 📋 Prerequisites

Before you start, make sure you have these installed:

- **Git** - [Download here](https://git-scm.com/downloads)
- **Node.js** (version 18 or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js)
- **A code editor** (VS Code, Cursor, etc.)

## 🔄 Step 1: Clone the Repository

1. Open your terminal (Command Prompt on Windows, Terminal on Mac/Linux)
2. Navigate to where you want to store the project:
   ```bash
   cd Desktop
   # or wherever you want to put the project
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/anirudhp15/debaite.git
   ```
4. Enter the project folder:
   ```bash
   cd debaite
   ```

## 🛠️ Step 2: Install Dependencies

Install all the required packages:

```bash
npm install --legacy-peer-deps
```

_Note: We use `--legacy-peer-deps` to avoid dependency conflicts_

## 🔑 Step 3: Set Up Environment Variables

1. Copy the example environment file:
   ```bash
   cp .env.example .env.local
   ```
2. Open `.env.local` in your code editor
3. **Ask me (Ani) for the actual environment variable values** and replace the placeholder values

## 🎯 Step 4: Run the Development Server

Start the app:

```bash
npm run dev
```

The app should now be running at `http://localhost:3000` 🎉

## 💻 Step 5: Open in Your IDE

1. Open your code editor (VS Code, Cursor, etc.)
2. Open the `debaite` folder in your editor
3. You're ready to start coding!

## 🔄 Working with Git (Making Changes)

When you want to make changes:

### Before you start working:

```bash
git pull origin main
```

### After making changes:

1. Check what you changed:
   ```bash
   git status
   ```
2. Add your changes:
   ```bash
   git add .
   ```
3. Commit your changes:
   ```bash
   git commit -m "Describe what you changed"
   ```
4. Push to GitHub:
   ```bash
   git push origin main
   ```

## 🆘 Common Issues & Solutions

### Issue: "next: command not found"

**Solution**: Make sure you ran `npm install --legacy-peer-deps` first

### Issue: Environment variable errors

**Solution**: Make sure your `.env.local` file has all the correct values (ask Anirudh)

### Issue: Port already in use

**Solution**: Check if the app is already running in another terminal, or use:

```bash
lsof -ti:3000
```

Then kill the process or use a different port.

### Issue: Git authentication problems

**Solution**: You might need to set up SSH keys or use personal access tokens. [GitHub Guide](https://docs.github.com/en/authentication)

## 📞 Need Help?

If you run into any issues:

1. Check the error messages carefully
2. Try the solutions above
3. Ask Anirudh! 😊

## 🎊 You're All Set!

Once everything is running, you should see the Debaite chat interface at `http://localhost:3000`. Happy coding! 🚀
