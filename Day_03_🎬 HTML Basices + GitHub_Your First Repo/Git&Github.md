🧠 1. What is Git? (Simple Explanation)

👉 Git = Version Control System

Means:

Tum apne code ka history track kar sakte ho Galti ho jaye → previous version pe wapas ja sakte ho Changes ka record maintain hota hai 📌 Real Life Example:

Socho tum Word file bana rahe ho:

Version1.doc Version2.doc Final.doc Final_Final.doc 😂

👉 Git kya karta hai? ➡️ Ye sab automatically manage karta hai ➡️ Tumhe alag-alag files banani nahi padti

🌐 2. What is GitHub?

👉 GitHub = Online storage for your code (Cloud + Sharing platform)

Git = Local (tumhare laptop pe) GitHub = Online (internet pe) 📌 Use: Code backup Team collaboration Portfolio (job ke liye important 🔥)

🛠️ 3. Install & Setup Git (Practical) ✅ Step 1: Download Git

👉 Google: Git download

✅ Step 2: Check Installation

Open terminal in VS Code and type:

git --version

✅ Step 3: Setup Git (VERY IMPORTANT) git config --global user.name "Your Name" git config --global user.email "your@email.com"

✅🔗 4. Create GitHub Account

👉 Go to: https://github.com

Steps: Sign up Username choose karo (professional rakho) Email verify karo

📂 5. First Git Project (Hands-on 🔥) Step-by-step:

folder banao
mkdir my-first-project

folder open karo
cd my-first-project

git start karo
git init

file banao
echo "Hello World" > index.txt

add file
git add .

save (commit)
git commit -m "First commit"

👉 Ab tumne apna first project bana liya 🎉

🔥 6. Connect to GitHub Step 1: GitHub pe repository banao Step 2: Connect karo git remote add origin https://github.com/username/repo-name.git git branch -M main git push -u origin main

👉 Ab tumhara code online hai 🚀

⌨️ 7. VS Code Shortcuts (Important 🔥) 🧑‍💻 Basic Shortcuts Shortcut Use Ctrl + S Save file Ctrl + C Copy Ctrl + V Paste Ctrl + Z Undo Ctrl + Shift + Z Redo

⚡ Coding Shortcuts Shortcut Use Ctrl + / Comment code Alt + ↑ / ↓ Line move Shift + Alt + ↓ Duplicate line Ctrl + D Select same word Ctrl + P File search Ctrl + Shift + P Command palette

Git Concepts

--> Repository - A Directory where git monitors your project files and records their revision history.

--> Clone - It created a local copy of a remote repository on your machine.

--> Stage - It Selects specific changes that you want Git to Include in the next Snapshot.

--> Commit - It records the staged changes as a permanent version in the project history.

--> Branch - Lets you Develop new features or experiment without affecting the main project.

--> Merge - Lets you develop new features or experiment without affecting the main project.

--> Pull - It Fetches and applies updates from a remote repository to your local one.

--> Push - Its Uploads your local commits to a remote repository

Git Repository Structure it Consists of 4 Parts:

Working Directory: This is your local directory where you make the project (write code ) and make changes to it.

Staging Area (or index): this is an area where you first need to put your project before committing. This is used for code review by other team members.

Local Repository: this is your local repository where you commit changes to the project before pushing them to the central repository on GitHub. This is What is provided by the distributed version control system. This corresponds to the .git folder in Our directory.

Central Repository: This is the main project on the central server, a copy of which is with every team member as a local repository.

All the repository structure is internal to Git and is transparent to the developer.

All the repository structure is internal to Git and is transparent to the developer.

{{ // transfer your project from working directory // to staging area. git add .

// transfers your project from staging area to // Local repository. git commit -m }}
