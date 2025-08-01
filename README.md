T&C Analyzer
Overview
The T&C Analyzer is a simple, yet powerful, web application designed to help users quickly understand the potential risks and legal implications of a Terms & Conditions or Privacy Policy document. By leveraging the power of a large language model, the application provides a concise summary and a risk rating from 1 to 10, highlighting clauses that may be deceptive, unfair, or overly broad.

The user-friendly interface is designed to be calm and easy to read, inspired by the aesthetic of modern AI assistants.

Features
AI-Powered Analysis: Utilizes the Gemini API to analyze complex legal text.

Risk Rating: Provides a numerical rating (1-10) to quickly gauge the potential risks of a document.

Detailed Explanation: Offers a clear, easy-to-understand summary of key clauses and concerns.

Responsive Design: Built with Tailwind CSS, the application works seamlessly on both desktop and mobile devices.

Relaxed UI: A green-themed, spaced-out interface designed for a calm and focused user experience.

Markdown Support: The AI-generated explanation is rendered from markdown to HTML for enhanced readability with proper formatting, including lists and bold text.

How to Use
Paste Text: Copy the text from any Terms & Conditions or Privacy Policy document.

Analyze: Paste the text into the provided text area.

Get Results: Click the "Analyze Text" button to get an instant risk rating and a detailed explanation of the findings.

Setup and Installation
This project is a single-page HTML file that requires no complex setup.

Obtain a Gemini API Key: You need to get an API key from Google's AI Studio.

Clone the Repository:

Bash

git clone https://github.com/Snorkel-Boy/Terms-And-Conditions-AI-Checker
Open the File: Open the index.html file in your preferred web browser.

Important Security Note
The provided code is an excellent starting point for a front-end application. However, the current implementation hardcodes the API key directly in the JavaScript file. This is not secure for a publicly deployed website.

To protect your API key and prevent unauthorized usage, it is strongly recommended to use a backend server or a serverless function as a proxy. This server-side component would securely store your API key in an environment variable and handle the communication with the Gemini API, ensuring your key is never exposed to the public.

Technologies Used
HTML5: For the basic structure of the web page.

Tailwind CSS: A utility-first CSS framework for rapid styling.

JavaScript: Powers the application's logic, including the API call and UI updates.

Gemini API: The core AI model that performs the analysis.

Marked.js: A client-side library used to parse markdown into HTML.

Contribution
Feel free to fork the repository and make improvements. Suggestions for new features, bug fixes, or design enhancements are welcome.

