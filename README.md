# The Ninth Door

**The Ninth Door** is a small mystical action-puzzle built for the web.

You move a point of light through nine symbolic chambers, collecting three fragments in each. Shadows pursue you, but there is no attack button. Your only power is a pulse that creates distance without destroying anything. Breath replenishes fastest when you stop moving.

The game is deliberately balanced around a simple idea: progress may require will, but survival also requires attention, restraint, and release.

## Play

Open `index.html` in any modern browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Controls

- **Move:** Arrow keys, WASD, or touch / drag anywhere in the chamber
- **Pulse:** Space bar or the on-screen Pulse button
- **Pause:** P, Escape, or the pause button
- **Mute:** M or the sound button

## Technical notes

- Plain HTML, CSS, Canvas, and JavaScript
- No dependencies, build step, tracking, or external assets
- Responsive layout and touch controls for phones and tablets
- Procedural visuals and Web Audio sound design
- Local best score saved in the browser

## GitHub Pages

This repository is ready to publish directly with GitHub Pages. Set Pages to deploy from the root of the default branch.

## License

MIT
