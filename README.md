React Project with Context API and Reducer
This project uses React's Context API and Reducer to manage state and mock data through JSON Server.

Installation
Clone the repository and install dependencies:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install
Install JSON Server globally:

bash
Copy
Edit
npm install -g json-server
Set up JSON Server to simulate an API:

Create a db.json file with mock data:
json
Copy
Edit
{
  "items": [
    { "id": 1, "name": "Item 1" },
    { "id": 2, "name": "Item 2" }
  ]
}
Start JSON Server:
bash
Copy
Edit
json-server --watch db.json --port 5000
Usage
Context API and Reducer are used for global state management.
AppContext.js creates the context, and appReducer.js handles state changes.
Key Commands
npm start: Runs the app in development mode.
npm run build: Builds the app for production.
npm test: Runs the tests.
Learn More
For detailed documentation on React, check out the official React Docs.
