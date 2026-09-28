# Connect-X starter

A starter UI for Connect-X, a platform for discovering people and joining topic-based rooms.

## Requirements
- Node.js LTS (https://nodejs.org)
- VS Code (https://code.visualstudio.com)
- Git (optional for local testing; needed for convenient GitHub uploads)

## Run on Windows
1. Extract the ZIP.
2. Open the extracted `connect-x` folder in VS Code.
3. In VS Code, choose Terminal → New Terminal.
4. Run:

```powershell
npm install
npm run dev
```

5. Open http://localhost:3000

## Upload to GitHub
1. Create a repository at https://github.com/new
2. Give it the name `connect-x`.
3. For the easiest upload, choose "uploading an existing file" on the empty repository page.
4. Drag the contents of this extracted folder into the GitHub upload area. Do not upload `node_modules` or `.env` files.
5. Commit the upload.

## Current status
This is a frontend starter with sample room data. Authentication, persistent database storage, private room enforcement, and live chat are not connected yet. These will be added in later steps using Supabase.
