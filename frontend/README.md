# Frontend — Lost and Found Portal

This folder contains the static frontend files (HTML + CSS) for the Lost and Found Portal.

## Important

These files are **mirrored** from the backend module:

```
backend/src/main/resources/static/
```

Spring Boot serves the frontend directly from that location. If you edit files in this
`frontend/` folder, you **must** apply the same changes to the corresponding files in
`backend/src/main/resources/static/` for them to take effect when the app is running.

## Files

| File | Description |
|---|---|
| `index.html` | Home page — browse lost/found items |
| `login.html` | Login page |
| `register.html` | User registration page |
| `item.html` | Item detail page |
| `post.html` | Post a new lost/found item |
| `my-claims.html` | User's claim history |
| `admin-claims.html` | Admin claims management |
| `css/index.css` | Main stylesheet |
| `css/alternate-ui.css` | Alternate UI styles |
| `css/login.css` | Login/register styles |
| `css/report.css` | Report page styles |
