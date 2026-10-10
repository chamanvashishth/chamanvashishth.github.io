# Chaman Vashishth — Personal Portfolio

A small, text-first portfolio for my projects, open-source work, experience, and learning notes.

**Live site:** [chamanvashishth.github.io](https://chamanvashishth.github.io/)  
**GitHub:** [@chamanvashishth](https://github.com/chamanvashishth) · **LinkedIn:** [Chaman Vashishth](https://www.linkedin.com/in/chamanvashishth/) · **Kaggle:** [chamanvashishth](https://www.kaggle.com/chamanvashishth)

---

## About

I’m an undergraduate studying **Internet of Things** at Dayalbagh Educational Institute, expected to graduate in 2028. I learn by building: implementing neural networks from scratch, experimenting with machine learning, developing web applications, and exploring quantum computing.

This site is meant to be a straightforward record of that work. It links to source code and demos where available, and distinguishes projects in progress from finished work.

## What’s on the site

- **Introduction** — my background and current interests
- **Projects** — 12 projects across machine learning, local AI, quantum computing, web development, and IoT
- **Open source** — selected repository work, pull requests, and contribution context
- **Community** — GSSoC’26, NSoc’26, SIH’26, and GSoC preparation
- **Experience** — internships, ongoing Web Developer work at Evara Yoga, and team projects
- **Toolkit** — languages, frameworks, and tools I’ve used in projects
- **Learning** — courses, credentials, and DSA practice
- **Contact** — email and professional profiles

## Selected projects

| Project | What it explores |
| --- | --- |
| [Neural Network from Scratch](https://github.com/chamanvashishth/neural-net-scratch) | A NumPy-based MNIST classifier with manual backpropagation and training components |
| [PredictX](https://github.com/chamanvashishth/PredictX) | Predictive maintenance using the AI4I dataset and interpretable ML workflows |
| [Movie Recommendation Engine](https://github.com/chamanvashishth/movie-recommender-als) | Collaborative filtering with ALS and SVD on MovieLens 1M |
| [ARIA](https://github.com/chamanvashishth/ARIA) | An in-development, local-first AI and neural-network learning project |
| [Quantum Laboratory](https://github.com/chamanvashishth/AIQCP) | A software-based environment for learning quantum computing concepts |
| [Evara Yoga](https://github.com/chamanvashishth/evarayoga) | A yoga and wellness website with class information and booking workflows |

See the [live portfolio](https://chamanvashishth.github.io/) for the full project list, technology stacks, and available demos.

## Design and implementation

The portfolio intentionally uses a minimal, editorial layout: readable typography, a single-column flow, plain links, and restrained separators. The goal is to keep attention on the work instead of interface effects.

- **HTML, CSS, and vanilla JavaScript** — no framework or build step
- Responsive layout for desktop and mobile
- Light and dark themes with a remembered preference when browser storage is available
- Searchable project list
- First-person portfolio guide with curated answers, working project/demo/contact links, and no external AI API
- Privacy-conscious client-side question matching; visitor questions are not sent to a chatbot service
- Keyboard-visible focus styles and reduced-motion support
- Semantic sections and descriptive page metadata

## Portfolio guide

The floating **Ask about my work** panel answers common questions about my ML projects, neural network implementation, open-source work, quantum projects, web development, and internship interests. It speaks in first person using curated, portfolio-backed answers and links to source repositories, demos, and contact channels. Unknown questions get a transparent fallback rather than an invented answer.

The guide is deliberately lightweight: it uses plain JavaScript and intent/keyword matching, does not call an external model or API, does not transmit visitor questions, and does not save chat history. It responds to greetings and small talk, has separate answers for Kaggle and GitHub projects, and covers professional projects, implementation details, reported metrics, open-source work, skills, and opportunity interests. Answers are written in first person to reflect my curious, practical learning style. Unknown or unsupported claims get a transparent fallback. It is a grounded portfolio navigator—not a general-purpose generative AI assistant.

Project metrics are kept tied to the source README. For example, the current Neural Network from Scratch README documents a 98.39% verified local test accuracy with 98.40% macro precision, 98.38% macro recall, and 98.39% macro F1. The recommender answer deliberately avoids treating a hard-coded RMSE as a guaranteed test result because its README says evaluation metrics are run-specific.

## Run locally

No package installation or compilation is required.

```bash
git clone https://github.com/chamanvashishth/chamanvashishth.github.io.git
cd chamanvashishth.github.io
```

Open `index.html` in your browser. For a local HTTP server, you can also run:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deploy

This repository is configured as a GitHub Pages-style personal site. To publish updates, push changes to the repository’s `main` branch and check the repository’s **Settings → Pages** configuration if deployment is not enabled.

## Updating content

Most portfolio content lives directly in `index.html`.

1. Edit the relevant section or project entry.
2. Keep project status and metrics accurate, and link to the source or demo when possible.
3. Test the page at mobile and desktop widths.
4. Commit and push your changes.

## Contact

- **Email:** [chamanvashishth133@gmail.com](mailto:chamanvashishth133@gmail.com)
- **GitHub:** [github.com/chamanvashishth](https://github.com/chamanvashishth)
- **LinkedIn:** [linkedin.com/in/chamanvashishth](https://www.linkedin.com/in/chamanvashishth/)
- **Kaggle:** [kaggle.com/chamanvashishth](https://www.kaggle.com/chamanvashishth)

---

Built and maintained by **Chaman Vashishth**.
