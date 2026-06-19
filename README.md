# AI Career Roadmap Generator

An interactive roadmap that helps learners explore AI career paths, identify the skills they already know, and build a personalized study plan.

## Live Demo

[Open the AI Career Roadmap Generator](https://ai-career-roadmap-ljfv.onrender.com)

## Features

- Eight AI career tracks: ML Engineer, Data Scientist, Computer Vision Engineer, AI Product Manager, AI/LLM Engineer, NLP Engineer, MLOps Engineer, and AI Research Scientist
- Shared foundations covering programming, mathematics, data wrangling, and core machine-learning concepts
- Search by course, skill, topic, career track, or job title
- Detailed course outlines, practical outcomes, difficulty levels, and time estimates
- Skill checkboxes that recalculate the remaining study time
- One-click personalized roadmap copying
- Responsive layout for desktop and mobile screens
- Accessible, dependency-free interface

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Render static-site hosting

No framework, package installation, backend, or build tool is required.

## Run Locally

Clone the repository:

```bash
git clone https://github.com/EliteYashu/ai-career-roadmap.git
cd ai-career-roadmap
```

Open `index.html` directly in a browser, or start a local static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy on Render

This repository includes a `render.yaml` Blueprint.

1. Sign in to [Render](https://dashboard.render.com/).
2. Select **New +** and then **Blueprint**.
3. Connect this GitHub repository.
4. Set the Blueprint name to `ai-career-roadmap`.
5. Deploy the Blueprint and wait for the service status to become **Live**.

Render automatically redeploys the site when new commits are pushed to the connected branch.

## Project Structure

```text
ai-career-roadmap/
|-- index.html    # Application markup, styles, data, and interactions
|-- render.yaml  # Render static-site configuration
`-- README.md    # Project documentation
```

## Author

Created by [EliteYashu](https://github.com/EliteYashu).
