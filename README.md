# Url-Shortener



This Python project is a simple URL shortener application built using Tkinter for the GUI and PyShorteners for URL shortening. The app allows users to input a long URL, shorten it using the TinyURL service, and copy the shortened URL to the clipboard with a single click.

Features:

User-Friendly Interface: Built with Tkinter, the app has a simple interface where users can easily input a URL and click to shorten it.
URL Shortening: Uses the pyshorteners library to shorten URLs via the TinyURL service.
Error Handling: Displays error messages if the input is invalid or if an issue occurs during URL shortening.
Clipboard Functionality: The app allows users to copy the shortened URL to the clipboard with a single button click.
Cross-Platform: Since it's built with Python and Tkinter, it works on Windows, macOS, and Linux.

Technologies Used:

Tkinter: Provides the graphical user interface (GUI).
PyShorteners: A Python library to shorten URLs using various URL shortening services.
TinyURL: The service used to shorten the URLs in this project.

How to Use:

Install dependencies: Install pyshorteners by running:
pip install pyshorteners

Run the app: 
Run the main.py script. The application will launch a simple window.

Enter URL: Type or paste the URL you want to shorten into the input field.
Click "Shorten": Press the "Shorten" button, and the shortened URL will appear below.
Copy to Clipboard: Once shortened, you can click "Copy Shortened URL" to copy the shortened URL to your clipboard.
Project Structure:
main.py: The main script that includes the Tkinter GUI and URL shortening functionality.
