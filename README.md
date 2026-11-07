# sample-repo

A minimal Node.js project for testing Jenkins and GitHub Actions.

## Run locally

```sh
cd backend
npm test
npm start
```

The backend responds with a JSON health message at `http://localhost:3000/health`.
The `Jenkinsfile` runs the backend tests and checks the frontend JavaScript syntax.