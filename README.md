🚀 How to Connect MongoDB and Deploy Project
link: https://www.youtube.com/watch?v=2r3zvYHSKA0
📌 MongoDB Setup (Atlas)
Go to MongoDB Atlas.

Create a new project.

Click Database, then create a cluster. Set up a username and password for database access.

Go to Network Access, add your IP, or allow access from anywhere (0.0.0.0/0).

To view your data online, go to your Cluster → Browse Collections.

⚙️ Backend Setup
Use CORS to allow your frontend to access your backend APIs.

Add your secrets in a .env file — do not upload this file to GitHub.

Upload only your backend folder to GitHub (excluding .env).

Deploy your backend on Render (Web Services). Add your environment variables in Render’s dashboard.

🎨 Frontend Setup
Add the backend URL (provided by Render) in your frontend project.

Create a vercel.json file to handle redirects and ensure your routes work properly.

Upload your frontend folder to GitHub.

Deploy your frontend on Vercel. Create a new project linked to your GitHub repo.

✅ Tip: Always keep your .env secrets safe and never commit them to your repository.
