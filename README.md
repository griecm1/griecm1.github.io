# Portfolio Site

Static portfolio page (`index.html` + `styles.css`) — no build step required.

## Publish with GitHub Pages

1. Create a new GitHub repo named exactly `griecm1.github.io`.
2. Push these files to it:
   ```
   git init
   git add index.html styles.css README.md
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/griecm1/griecm1.github.io.git
   git push -u origin main
   ```
3. Wait a minute, then visit `https://griecm1.github.io`.

(No GitHub Pages settings changes needed for a `<username>.github.io` repo — it publishes automatically from `main`.)

## Local preview

```
python -m http.server 4321
```
then open http://localhost:4321

 