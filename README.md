# Todo App — React PR 9

A **Todo list** app built with **React**, **Redux Toolkit**, **Vite**, and **Bootstrap**. Todos are stored in **Firebase Realtime Database** via the REST API (`axios`).

## Links

| | |
| --- | --- |
| **Repository** | [github.com/anashali01/React_PR_9](https://github.com/anashali01/React_PR_9) |
| **Live demo** | **[Replace with your deployed URL](https://YOUR-LIVE-DEMO-URL)** |

After you deploy the production build (for example with [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or Firebase Hosting), edit this README and set **Live demo** to your real public URL.

## Output / preview

![Application preview — Add Todo form and todo table](./docs/app-preview.png)

*If the image does not show locally, add a screenshot at `docs/app-preview.png`, or use the full URL after pushing:*  
`https://raw.githubusercontent.com/anashali01/React_PR_9/main/docs/app-preview.png`

## Features

- Add new todos with a title
- List todos in a table
- Update an existing todo
- Delete a todo
- Data persisted through Firebase Realtime Database

## Tech stack

- React 19, Vite 8
- Redux Toolkit, React Redux
- Axios
- Bootstrap 5
- Firebase Realtime Database (REST)

## Run locally

```bash
npm install
npm run dev
```

Build for production:

```bash
npm run build
npm run preview
```

## Firebase

The app uses a configured Firebase Realtime Database base URL in `src/api/apiInstance.js`.
