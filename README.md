# Eisenhower Matrix

A minimal, dark-themed productivity tool that visualizes your tasks as dots on an urgency/importance graph -- helping you decide what to do first, schedule, batch, or park.

<!-- screenshot -->

## Live Demo

[https://eisenhower-matrix-5eynu35at-nandinis-projects-49e34ec0.vercel.app](https://eisenhower-matrix-5eynu35at-nandinis-projects-49e34ec0.vercel.app)

## Features

- **Dot-only visual graph** -- tasks are colored dots positioned on a 2D urgency vs. importance plane
- **Click to expand dots** -- click any dot to see task details, assign a goal, start a timer, complete, or delete
- **Click-to-add tasks on the graph** -- click any empty spot on the graph to place a new task right where it belongs
- **Drag-and-drop between quadrants** -- drag dots to reposition them or move tasks across quadrants
- **Right-click context menu** -- quickly start a timer, mark complete, move to any quadrant, send to backlog, or delete
- **Fullscreen 45-minute timer** -- immersive focus timer with pause, done, and cancel controls plus a progress bar
- **Time tracking per task** -- accumulated time is recorded and displayed for each task
- **Goal alignment** -- define high-level goals and link tasks to them to stay intentional
- **Backlog zone** -- park tasks you are not ready to prioritize; drag them back onto the graph when the time comes
- **Daily progress chart** -- a canvas-rendered bar chart tracking completions over time
- **Double-click to toggle complete** -- fast way to mark tasks done without opening a popup

## Quadrants

| Quadrant | Color | Meaning |
|----------|-------|---------|
| **Do First** | Green | Urgent and important |
| **Schedule** | Yellow | Important but not urgent |
| **Batch** | Blue | Urgent but not important |
| **Park** | Red | Neither urgent nor important |

## How to Use

**Locally:** open `index.html` in any modern browser. No build step, no server required.

**Online:** visit the [live demo](https://eisenhower-matrix-5eynu35at-nandinis-projects-49e34ec0.vercel.app).

### Quick Start

1. Click anywhere on the graph to add a task at that position
2. Use the input bar below the graph to add tasks to a specific quadrant
3. Click a dot to expand it -- start a timer, assign a goal, or mark complete
4. Right-click a dot for quick actions (move, complete, delete, backlog)
5. Drag dots to reposition them across the graph
6. Define goals in the Goals section and link tasks to stay aligned

## Tech

- Pure HTML, CSS, and JavaScript -- zero dependencies
- Single `index.html` file
- All data persisted in `localStorage`
- Canvas-rendered progress chart
