🌙 Dark Notes

A modern dark-themed notes app built with HTML, TailwindCSS, and JavaScript.
It allows users to create, edit, pin, color-code, and search notes with a smooth UI and animated particle background.

This project focuses on clean UI design, smooth animations, and efficient note management.

✨ Features

📝 Create and edit notes

🎨 Color-coded notes

📌 Pin important notes

🔍 Real-time note search

📊 Word counter per note

🌌 Animated particle background

💾 Persistent data storage

🗑 Delete confirmation system

📱 Fully responsive design

🖼 UI Overview

The interface includes:

Header with note count and search

Grid layout for notes

Floating Action Button (FAB) to create notes

Modal editor for writing notes

Toast notifications for actions

Particle animation background

🛠 Technologies Used

HTML5

JavaScript (Vanilla JS)

Tailwind CSS

Lucide Icons

📂 Project Structure
dark-notes/
│
├── index.html      # Main application file
├── README.md       # Documentation

Everything is contained in one file for simplicity and portability.

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/yourusername/dark-notes.git
2️⃣ Open the project

Simply open:

index.html

in your browser.

No build tools or installation required.

🧠 How It Works
Notes System

Notes contain:

note_id

title

content

created_at

updated_at

pinned

color

They are managed using a data layer connected to:

window.dataSdk
Particle System

The background animation uses a custom particle engine built with the HTML Canvas API.

Particles:

move slowly

fade out over time

respond to actions like creating notes

Configurable UI

The app supports dynamic configuration through:

window.elementSdk

Allowing:

theme colors

fonts

font sizes

UI customization

📱 Keyboard Shortcuts
Shortcut	Action
Ctrl + N	Create new note
Esc	Close modal
🔮 Future Improvements

Possible upgrades:

Cloud syncing

Markdown support

Tag system

Dark / light theme switch

Export notes as PDF

AI note summarization

📜 License

This project is open source and free to use.

⭐ If you like this project, consider starring the repository!
