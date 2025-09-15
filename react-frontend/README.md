
# React-frontend – REACT (CRA) + TypeScript

## Quick start
```bash
cd react-frontend
npm i
npm start
```
Default API: `http://localhost:1337/api`. Override with - cp .env.example .env:
```
REACT_APP_API_URL=http://localhost:1337/api
```
## APIs end-points
1- Get Mood Entries = GET /mood-entries
2- Get Teams = GET /teams
3- Create Mood Entries = Post /mood-entries

## Features
- Submit mood (username, mood, comment, optional team)
- Latest entries list
- Mood distribution (Pie) and trend (Line) charts
- Filters by username or team
- Material UI used for CSS
- Clean, responsive UI

## Bonus
✨ Toast Notifications
    - Implemented using React-Toastify for success/error alerts.

✨ API Integration
    - Axios for HTTP requests with error handling.
