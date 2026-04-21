# Squint Logo Animation

An interactive animation playground built around the Squint logomark. Two animation modes, fully tweakable controls, and GIF export.

**Live:** https://novia-chao.github.io/logo-animation/

---

## Modes

**Dot Fill** — The logomark shape is filled with a grid of dots that pulse in a wave across the form.

**Logo Grid** — A rectangle tiled wall-to-wall with the logomark. Each tile animates independently or in a wave.

## Controls

| Control | Description |
|---|---|
| Speed | Wave cycles per second |
| Wave width | How wide the wave band is relative to the shape |
| Direction | → ← ↑ ↓ ◎ ⤢ Blink — axis the wave travels along, or random independent blink |
| Color | Dot / logo fill color |
| Min / Max opacity | Brightness range of the pulse |
| Pulse mode | Animate opacity, scale, or both |
| Dot size / Spacing | Dot Fill only — controls grid density |
| Tile size / Gap | Logo Grid only — controls tile density |
| Width / Height | Logo Grid only — canvas dimensions |
| Aspect ratio | Lock to 1:1, 4:3, or 16:9 |

## Export

Select a duration (3s / 5s / 10s / 15s) and click **● Rec** to capture a looping GIF of whichever view is active. The file downloads automatically when rendering is complete.

## Updating

After editing `logo-animation.html` locally:

```bash
cp /Users/novia/squint/logo-animation.html ~/logo-animation/index.html
cd ~/logo-animation && git add index.html && git commit -m "Update animation" && git push
```
