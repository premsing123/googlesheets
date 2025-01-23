 # Web Application Mimicking Google Sheets

The **Web Application Mimicking Google Sheets** Project is a web-based application designed to provide seamless integration with Google Sheets using a robust full-stack architecture. It features a modern frontend built with React and Vite and a backend powered by Node.js, Express.js, and MongoDB.

---

## Features

- **Web Application Mimicking Google Sheets**: Perform CRUD operations with Google Sheets data.

- **Modern UI**: Built with React and styled for a sleek user experience.

-**Scalable Backend**: Node.js and Express.js backend with MongoDB for data persistence.

-**Responsive Design**: Optimized for all screen sizes.

---

## Technologies Used

-**Frontend**: React, Vite

-**Backend**: Node.js, Express.js

-**Database**: MongoDB

---

## File Structure

google-sheets/
├── client/          # Frontend code (React + Vite)
├── server/          # Backend code (Node.js + Express.js)
├── .prettierrc      # Prettier configuration
├── .git/            # Git version control
'''

---

## Setup Instructions

### 1.Prerequisites

- Node.js (v16 or higher recommended)

- MongoDB (local or cloud instance)

- Git

- Installation

### 2.Clone the Repository:

- git clone <repository-url>
- cd google-sheets

#### 3.Install Dependencies:

## Navigate to the client directory and install frontend dependencies:

- cd client
- npm install

## Navigate to the server directory and install backend dependencies:

- cd ../server
- npm install

### 4.Environment Variables:

## Create a .env file in the server directory and configure the following variables:

- PORT=5000
- MONGODB_URI=<your-mongodb-uri>
- GOOGLE_API_KEY=<your-google-api-key>

## 5.Start the Development Servers:

## Frontend:

- cd client
- npm run dev

## Backend:

- cd ../server
- npm start

### 6.Access the Application:
- Open your browser and navigate to http://localhost:3000 (default React app port).
- Executed output **https://www.loom.com/share/f70915e693fa4721853001e3f241256c?sid=7bd1f165-fab1-4777-86e4-7f658b7ce455**

## Usage Instructions

- Authenticate with your Google account to link Google Sheets.

- Perform operations like reading, writing, and updating data in Google Sheets directly from 
  the app.

## Customization

### Update Chatbot Responses

The responses are generated using Hugging Face's transformers. To modify the model or fine-tune it for specific intents:

- Open app.py and locate the model initialization:

from transformers import pipeline
model = pipeline("text-generation", model="gpt2")

- Replace gpt2 with a different model or adjust the pipeline settings.

### Modify Frontend

- **HTML**: Edit templates/chat.html for structural changes.

- **CSS**: Update style.css for design customizations.

- **JavaScript**: Modify script.js for additional interactivity.

---

## License

This project is licensed under the MIT License:

'''

MIT License

Copyright (c) 2025 Munna Reddy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
'''

---

## Acknowledgments

- **Hugging Face**: For providing state-of-the-art NLP models.

- **Flask Documentation**: For clear and concise guides.

- **Bootstrap**: For enabling a responsive and polished design.

---

## Contact

For any queries or feedback, feel free to reach out:

**Munna Reddy**  
-Email: reddymunna148@gmail.com
-GitHub: (https://github.com/Munna148)

