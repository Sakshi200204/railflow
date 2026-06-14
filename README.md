# railflow
AI-powered railway crowd-flow management platform with a digital twin, predictive risk analysis, operator controls, incident simulation, explainable recommendations, and what-if decision support for safer and more efficient stations.

## Live Application

**Deployed App:** https://railflow-ai.netlify.app

### Demo Credentials

| Role | Employee ID | Password |
|---|---|---|
| Station Controller | `controller` | `demo123` |
| Operations Manager | `manager` | `demo123` |
| System Administrator | `admin` | `demo123` |

## Project Overview

Railway stations experience highly dynamic passenger movement. A platform change, delayed train, blocked foot-over bridge, simultaneous arrival, festival rush, or emergency instruction can quickly create dangerous congestion.

RailFlow AI provides a visual command centre where operators can:

- observe zone-wise passenger density,
- monitor inflow and outflow,
- identify bottlenecks,
- forecast short-term crowd build-up,
- simulate incidents,
- compare possible interventions,
- understand why an action is recommended,
- and estimate the operational impact of that action.

The current version is a browser-based functional prototype implemented as a single-page HTML application.

---

## Problem Statement

Crowd management at large railway stations is often reactive.

Operators may notice a problem only after:

- a foot-over bridge becomes overloaded,
- a platform reaches unsafe density,
- entry gates become blocked,
- exit-side movement slows,
- train delays increase passenger dwell time,
- or a platform change redirects passengers through the same route.

This creates several operational challenges:

- slow response time,
- poor visibility across station zones,
- limited ability to compare interventions,
- difficulty estimating the result of an action,
- inconsistent decision-making,
- and dependence on manual observation.

A preventive system should help operators identify risk early and test possible actions before implementing them.


## Core Objectives

RailFlow AI is designed to demonstrate how railway crowd-flow operations can become:

- **Safer** through earlier congestion detection.
- **Smarter** through explainable decision support.
- **More efficient** through action comparison and simulation.
- **More resilient** through scenario planning.
- **More transparent** through a live activity timeline.


## Running Locally

### Method 1: Open Directly

1. Download the repository.
2. Locate `index.html`.
3. Double-click the file.
4. Open it in Chrome, Edge, or Firefox.

### Method 2: Run a Local Static Server

Using Node.js:

```bash
npx server .
```
Using Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## License

This project is intended for educational, hackathon, research-concept, and portfolio demonstration purposes.

For production or commercial use, the system would require:

- validated data,
- railway-domain review,
- security assessment,
- operational approvals,
- and real-world testing.
