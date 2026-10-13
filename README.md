# Tanjaya Jason Winata — AI Engineer Portfolio

Source for [tanjaya.vercel.app](https://tanjaya.vercel.app/), a single-page portfolio focused on AI engineering, software systems, and selected public work.

## About me

I'm an AI Engineer and Software Engineer building practical applications around LLMs, agentic workflows, and retrieval-augmented generation. I focus on the backend services, data systems, and interfaces that make AI useful beyond a prototype.

## Tech stack

| Area | Tools and concepts |
| --- | --- |
| AI and data | Python, LLMs, RAG, AI agents, Ollama, ChromaDB |
| Backend | FastAPI, PostgreSQL, REST APIs, Vanna AI |
| Frontend | Next.js, React, TypeScript, JavaScript |
| Workflow | Linux, Git |

## What is on the site

- An AI engineering introduction and current areas of focus
- Featured projects: Agentic RAG + Text2SQL, Jak Air, and TLPI Bidang 4
- A tech stack aligned with the [public GitHub profile](https://github.com/TanjayaJason)
- Experience, education, and professional contact links

The interface uses plain HTML, CSS, and JavaScript. It has no build step, runtime dependencies, analytics, or contact form. Scroll reveals and ambient motion use `IntersectionObserver` and `requestAnimationFrame`; the site respects reduced-motion preferences and keeps content visible when JavaScript is unavailable.

## Run locally

From the repository root:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## Edit the portfolio

| Content | File |
| --- | --- |
| Bio, projects, links, metadata | `index.html` |
| Layout, colors, responsive design, motion | `css/portfolio.css` |
| Navigation, scroll effects, reveal logic | `js/portfolio.js` |
| Project image | `images/jakair.jpg` |

Project descriptions are based on their public repositories. Update the text in `index.html` when a project changes. The earlier template files in `css/`, `js/`, and `scss/` are retained for reference but are not loaded by the current page.

## Privacy

The page links to public GitHub and LinkedIn profiles. It does not publish a phone number, street address, birth date, direct email address, or downloadable CV. Before adding personal information, review what would become publicly accessible in the site and repository.
