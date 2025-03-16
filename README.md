# AI Powered Email Reply Generator

## Project Overview
The AI-Powered Email Reply Generator is an intelligent system that automates email responses using AI. Built with a Spring Boot backend and a React.js frontend, this project includes a browser extension that seamlessly integrates with email platforms. When enabled, the extension provides an "AI Reply" button that generates AI-powered responses based on the email's content.

## Features
**i) _Automated Email Replies_:** Uses AI to generate context-aware email responses.<br/>
**ii) _Spring Boot Backend:_** Handles AI processing, API requests, and response generation.<br/>
**iii)_React.js Frontend:_** Provides a user-friendly interface for configuration and interaction.<br/>
**iv)_Browser Extension:_** Integrates with email platforms to add an "AI Reply" button for quick responses.<br/>
**v)_Customizable Responses:_** Users can tweak AI-generated replies before sending.<br/>
**vi)_Seamless Integration:_** Works with various email services without disrupting workflow.<br/>

## How It Works
**i) _User Receives an Email:_** The browser extension detects incoming emails.<br/>
**ii) _AI Reply Button Appears:_** If the extension is enabled, an "AI Reply" option becomes available.<br/>
**iii) _AI Generates a Response:_** When clicked, the backend processes the email content and generates a suggested reply.<br/>
**iv) _User Reviews and Sends:_** The user can modify or send the AI-generated response.<br/>

## Tech Stack
**i) _Backend:_** Spring Boot, Java<br/>
**ii) _Frontend:_** React.js, JavaScript, Material UI<br/>
**iii) _AI Model:_** Google Gemini 2.0 Flash<br/>

## Installation & Setup
**1) _Clone the repository:_**<br/> 
    git clone https://github.com/Bikram2473/email-reply-generator.git<br/>
    cd email-reply-generator

**2) _Navigate to backend directory:_**<br/>
    cd email-writer-sb

**3) _Build and run the Spring Boot application:_**<br/>
    mvn spring-boot:run

**4) _The backend runs on http://localhost:8080._**

## Frontend Setup (React.js)
**1) _Navigate to frontend directory:_**<br/>
    cd email-writer-react

**2) _Install dependencies:_**<br/>
    npm install

**3) _Start the development server:_**<br/>
    npm start

**4) _The frontend runs on http://localhost:3000_**

## Browser Extension Setup
**1) _Navigate to the extension directory._**<br/>
**2) _Load the extension in Chrome:_**<br/>
      -----> Open chrome://extensions/<br/>
      -----> Enable Developer Mode (top-right).<br/>
      -----> Click Load unpacked and select the extension folder.<br/>
      
**3) _Enable the extension and open an email to see the AI reply button._**

## Results


## Usage
**---> _Manual AI Reply Generation:_** Use the React UI to enter email text and get a response.<br/>
**---> _Automatic Reply in Emails:_** Enable the browser extension to generate replies directly within email clients.

