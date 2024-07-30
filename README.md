The Editor
LiveDocs is a real-time collaborative document editing application, inspired by Google Docs. Built with Next.js for the user interface, Liveblocks for real-time features, and styled with Tailwind CSS, this project showcases advanced web development skills and creates a seamless collaborative experience.

🌟 Features
Authentication: Secure user authentication using GitHub via NextAuth.
Collaborative Text Editor: Real-time collaborative editing for multiple users.
Document Management:
Create: Easily create and auto-save new documents.
Delete: Remove documents you own.
Share: Share documents via email or link with customizable permissions.
List: View all owned or shared documents with search and sorting options.
Comments: Add inline and general comments, with threaded discussions.
Active Collaborators: See real-time indicators of active collaborators.
Notifications: Get notified about document shares, new comments, and collaborator activities.
Responsive Design: Optimized for all devices.
🛠 Tech Stack
Next.js
TypeScript
Liveblocks
Lexical Editor
ShadCN
Tailwind CSS
🚀 Quick Start
Follow these steps to set up the project locally:

Prerequisites
Ensure you have the following installed:

Git
Node.js
npm (Node Package Manager)
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/adrianhajdin/collaborative-editor.git
cd collaborative-editor
Install Dependencies:

bash
Copy code
npm install
Set Up Environment Variables:
Create a .env file in the root directory with the following content:

makefile
Copy code
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
Replace the placeholder values with your actual Clerk & Liveblocks credentials.

Running the Project:

bash
Copy code
npm run dev
Open http://localhost:3000 in your browser.

🧑‍🤝‍🧑 Community
Need help or want to contribute? Join our active Discord community with over 34k+ members. It's a great place to ask questions, report bugs, and share your experience.

📄 License
This project is licensed under the MIT License.


