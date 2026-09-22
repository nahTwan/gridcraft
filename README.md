# GridCraft

GridCraft is a full-stack Formula racing strategy simulator. Players manage a
real-world team through Monaco, Belgium, and Brazil, make live pit-wall
decisions, and review how those decisions affect race and championship results.

> GridCraft is an unofficial educational project and is not associated with or
> endorsed by Formula 1, the FIA, any team, or any driver.

## Project Status

Planning and product design.

## Planned Experience

- Build a tire and pit-stop strategy before each race.
- Manage both drivers during a lap-by-lap simulation.
- Intervene at any time or respond only to major race events.
- React to weather, safety cars, traffic, and tire degradation.
- Compare the planned strategy with the actual outcome.
- Carry results through a three-race championship.

## Initial Championship

1. Monaco
2. Belgium (Spa-Francorchamps)
3. Brazil (Interlagos)

## Planned Technology

- React and TypeScript
- Spring Boot
- PostgreSQL
- Python for data analysis and model training
- Docker Compose
- GitHub Actions

## Repository Layout

```text
gridcraft/
├── frontend/   # React client
├── backend/    # Spring Boot API and simulation engine
├── data/       # Analysis, model training, and data documentation
└── docs/       # Product and technical decisions
```

## Development Approach

The first release is intentionally scoped as a polished portfolio project. It
uses production-style organization, tests, documentation, and automation
without unnecessary large-scale infrastructure.


## Why I'm Building This

I've been watching Formula 1 since eighth grade, and I wanted to build a project around something I enjoy. With GridCraft, I want to improve my full-stack development skills and learn how to use race data to simulate strategy decisions.
