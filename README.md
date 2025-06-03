📂 File Metadata Extractor - Uncover File Secrets! 🚀
Hey there, file explorer! 🌟 Welcome to the File Metadata Extractor, a super sleek Flask app that lets you upload files and reveal their metadata in style! 🎉 With a black-themed UI, a floating folder animation, and a terminal display that glows with a white shadow, this app is as cool as it is useful. Built with Python, Flask, and jQuery – let’s dig into those files! 💻
✨ What’s This All About?
Upload any file and this app will extract its metadata, showing you:

File name, size, type, and last modified date – all in a snap!
A stunning UI with a floating folder that tilts on hover.
A terminal-style display at the bottom, glowing with a white shadow to show your metadata.

It’s perfect for developers, tech enthusiasts, or anyone curious about their files’ hidden details! 🔍
🔥 Features That’ll Blow Your Mind!

Metadata Extraction: Get file name, size, type, and last modified date instantly!
Floating Folder: A 3D folder animation that floats and tilts – pure magic! ✨
Terminal Display: A sleek terminal with a white shadow to show your metadata in style.
Black Theme: High-contrast design that looks amazing on any device.

🛠️ Get Started in Seconds!
Ready to uncover file secrets? Let’s do this! 🎉

Clone the Repo (You’re gonna love this!):git clone https://github.com/your-username/file-metadata-extractor.git
cd file-metadata-extractor


Set Up a Virtual Environment (Optional but awesome!):python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install the Goodies:pip install flask


Run the App (Here comes the fun!):python app.py


Open your browser and go to http://localhost:5000. Upload a file and watch the metadata appear in the terminal! 🚀

🖱️ How to Use It

After running the app, visit http://localhost:5000.
Click the "Upload File" button and select a file from your device.
The terminal will display the file’s metadata, including name, size, type, and last modified date.
Enjoy the floating folder animation and sleek terminal display! 🎨

📁 What’s Inside?

app.py: The Flask app that handles file uploads and extracts metadata (name, size, type, last modified).
templates/index.html: The front-end UI with the folder animation, file upload input, and terminal display.
static/style.css: The CSS magic for the black theme, floating folder, and terminal with a white shadow.

💡 Pro Tips

Extend Metadata: Want more details (e.g., EXIF data for images)? Install Pillow (pip install Pillow) and modify app.py to extract EXIF data for images!
File Types: The app uses mimetypes to guess file types. If a type is "Unknown," it’s because the file extension isn’t recognized by mimetypes.
Security: The app deletes files after processing, but always validate uploads in production to prevent security risks.

🚀 Join the Adventure!
Got ideas to make this even cooler? Want to add more metadata fields or support for specific file types? We’d LOVE to hear from you! Open an issue or submit a pull request – let’s make this app even more amazing together! 🤝
📜 License
This project is licensed under the MIT License – feel free to use, share, and modify it! See the LICENSE file for details.
🙌 Big Thanks!
Shoutout to the awesome tools that made this possible:

Flask for the web framework.
jQuery for easy DOM manipulation and AJAX.

Let’s uncover file secrets together! 📂 Happy coding! 💻
