Influence OS: AI-Powered LinkedIn Automation Tool
A comprehensive AI agent that autonomously generates, schedules, and analyzes professional social media content.

🚀 Project Overview
This project, Influence OS, is an AI-driven tool designed to help professionals manage their LinkedIn presence and personal brand. The application acts as a personal branding AI agent, capable of analyzing a user's professional profile, researching real-time industry trends, and generating engaging content in multiple formats. It features a simple web-based user interface, allowing for easy content generation, scheduling, and performance tracking.

✨ Key Features
This project was built to meet a set of core and bonus requirements, demonstrating a full-stack AI development workflow.

Core Functionalities

User Profile Analysis: Analyzes user data (role, skills, interests) to create personalized content.

Industry Research: Scrapes Google News and Reddit to find the latest industry trends and news.

Content Generation: Creates professional LinkedIn posts, including A/B-tested text posts and multi-slide carousels.

Engagement Optimization: Includes sentiment analysis and suggests relevant hashtags for maximum reach.

Performance Analytics: Tracks and displays simulated post analytics (likes, comments, etc.).

Automated Posting: Provides a framework for scheduling and publishing content to multiple social media platforms (LinkedIn, Twitter, Facebook, Reddit).

Compliance & Ethics: Implements a basic compliance check to flag potentially inappropriate content.

Bonus Features

AI-powered Image Generation: Uses a Stable Diffusion model to create custom, professional graphics for posts.

Competitor Analysis: Scrapes news headlines related to a specific competitor to inform content strategy.

Sentiment Analysis: Provides a sentiment score for each generated post to gauge its potential reception.

Network Growth Strategies: An AI agent generates personalized, actionable strategies for growing the user's professional network.

Multi-language Support: Content can be generated in multiple languages.

Integration with Other Platforms: The code is structured to post to various social media platforms via their respective APIs.

⚙️ Getting Started
Prerequisites

A Google account to run the project in Google Colab.

API keys for the social media platforms you wish to integrate (e.g., Twitter, Facebook).

An ngrok authentication token to create a public URL for your application.

Setup Instructions

Open the Google Colab Notebook: The entire project is contained within a single notebook.

Install Dependencies: Run the first code cell to install all necessary Python libraries.

Configure ngrok: Run the ngrok setup cell. You will need to provide your ngrok authentication token.

Add Your API Keys (Crucial): In the main functions cell, replace all "YOUR_..." placeholder strings with your actual API keys and tokens.

Security Note: It is highly recommended to remove these hardcoded credentials before saving the notebook to a public repository. A separate, private notebook or environment variables are the best practice for storing sensitive information.

Run the Server: Execute the final cell to start the Flask server. It will provide a public URL for your application via ngrok.

💻 Usage
Once the server is running and the public URL is active, navigate to the URL in your browser to access the web application.

Content Generator Tab:

Fill in your profile details, a research keyword, and select your desired post type (Text or Carousel).

Click "✨ Generate Content" to see the AI's output, including post text, images, and analytics.

Select a date and time, then click "⏳ Schedule Post" to add it to your calendar.

Content Calendar Tab:

View all your scheduled posts in a simple calendar format.

Click on a post entry to see its simulated performance analytics (likes, comments, etc.).

Growth Strategies Tab:

Click "💡 Generate Strategies" to receive personalized, AI-generated tips for expanding your professional network.

📁 Repository Structure
The project is structured as a single Google Colab notebook for ease of use and demonstration.

Cell 1: Library installations.

Cell 2: ngrok setup for creating a public URL.

Cell 3: All core Python functions, AI model loading, and social media API placeholders.

Cell 4: The Flask web server logic and the HTML/CSS/JavaScript for the frontend.

Cell 5: The final command to run the Flask server and start the application.

📄 Project Deliverables
Working Application: A fully functional web application accessible via a public URL.

Source Code: The complete, well-documented source code in a Google Colab notebook.

API Documentation: In-line comments and instructions on how to use and integrate APIs.

Technical Report: An overview of the architecture and implementation decisions.

User Guide: Step-by-step instructions for setup and usage.

🔒 Security
For a production environment, all credentials (API keys, tokens, etc.) should be stored securely as environment variables and never hardcoded or committed to a public repository.

📜 License
This project is licensed under the MIT License.
