# Smart Library Frontend

React and Vite client for the Smart Library application.

## Development

```sh
npm install
npm run dev
```

Set `VITE_API_BASE_URL` to the backend API URL when building or running in a deployed environment. It defaults to `http://localhost:8080`.

## Production build

```sh
npm run build
```

The Dockerfile builds the client and serves it with Nginx. Pass `VITE_API_BASE_URL` as a Docker build argument when deploying.

Backend repository: https://github.com/kasarla06072005-dev/smart-library-backend
