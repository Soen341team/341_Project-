 Overview:
  Docsify – A Real-Time Collaborative Editor
Docsify is a collaborative document editing app built with Next.js. It lets users chat in groups, send direct messages, and edit documents together in real time. The goal is to create a simple, fast, and modern alternative to Google Docs while making sure it includes all the required features.

 Tech Stack:
Frontend: Next.js, TypeScript, TailwindCSS, ShadCN
Real-Time Collaboration: Liveblocks
Text Editor: Lexical Editor
Authentication: NextAuth (GitHub OAuth)
Database: NeonDB
Hosting & Deployment: Vercel
 --------------------------------------------------------------------

 Core Features (All Requirements Met ✅)
1️⃣ Group Chat (Text Channels) ✅
Users can join different chat rooms ( "General," "Project Help," "Social").
Messages are visible to everyone in the channel.
Real-time chat updates with Liveblocks.
Clean and modern UI using ShadCN and TailwindCSS.
2️⃣ Private Messaging (DMs) ✅
Users can send direct messages to others.
Supports real-time updates, typing indicators, and read receipts.
Messages are securely stored in the database.
3️⃣ Role-Based Permissions ✅
Admins can:
✅ Create and delete channels.
✅ Moderate (delete) messages if needed.
Members can:
✅ Send and view messages, but cannot manage channels.
➕ Extra Feature: Live Document Editing (Like Google Docs)
Since this project is about collaboration, we are also adding a real-time text editor where multiple users can edit the same document at the same time.
 --------------------------------------------------------------------
Live Editing: Multiple users can edit documents together.
Document Management: Users can create, delete, list, and share documents.
Search & Sorting: Find documents easily.
Inline Comments: Users can leave comments and reply in threads.
Active Collaborators: Show who's currently editing.
Notifications: Alerts for new comments, edits, or shared docs.
👥 Contributors:
Yahya Mounadi (40234117)
