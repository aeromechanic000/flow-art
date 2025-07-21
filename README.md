# Flowart

Web Application: [Flowart](https://makedown.vercel.app/)

A web app to create and edit flowcharts.

![Screenshot 2025-07-07 at 23.11.59.png](https://s2.loli.net/2025/07/07/5wmL2Vnzku6GHhp.png)

Author's webpage: [aeromechanic.fun](https://aeromechanic.fun)

## Prompt to Create Flow

```
Create a flowchart JSON for: "{prompt}". Return only valid JSON with "shapes" array (id, type, x, y, width, height, text, color) and "arrows" array (id, startId, startPoint, endId, endPoint, color). Use types: rectangle, ellipse, diamond, hexagon. Use colors: ["#e3f2fd", "#f3e5f5"]}.
```
