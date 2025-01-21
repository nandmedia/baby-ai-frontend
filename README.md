# Baby AI Frontend

This is the frontend for the Baby AI project. It is built using React.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/baby-ai.git
   cd baby-ai/frontend
2. Install dependencies:

bash
Copy
Edit
npm install

3. Start the development server:

bash
Copy
Edit
npm start

4. Visit the app on http://localhost:3000.

5. 
---

### **Backend: `backend/package.json`**

The backend uses Node.js and Express, and the `package.json` here would look like this:

```json
{
  "name": "baby-ai-backend",
  "version": "1.0.0",
  "main": "server.js",
  "dependencies": {
    "express": "^4.17.1",
    "mongoose": "^5.10.0",
    "dotenv": "^8.2.0",
    "cors": "^2.8.5",
    "body-parser": "^1.19.0"
  },
  "devDependencies": {
    "nodemon": "^2.0.7"
  },
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js"
  }
}
