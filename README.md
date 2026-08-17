# Rhythm

Rhythm is a local-first habit and routine tracker with flexible weekly goals, streaks, reflections, history editing, and browser-data backups.

## Run locally

Open this folder in a terminal and run:

```sh
python3 -m http.server 4173
```

Then visit `http://127.0.0.1:4173`.

## Data and privacy

Rhythm stores its data in the browser's local storage. It does not send habits or reflections to a server. Users should use **Data & backup** to export a backup before clearing browser data or moving to a different browser/device.

## Deploy on Render

1. Push this project to a GitHub repository.
2. In Render, select **New → Blueprint** and connect the repository.
3. Render will detect `render.yaml`. Change the `name` in that file first if `rhythm-habit-tracker` is already taken.
4. Review the generated Static Site and deploy it.

The deployment is static: each visitor has their own local browser data and does not receive an account or cross-device sync.
