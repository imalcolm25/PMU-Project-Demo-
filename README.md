This is an example space for adding an overview of your project

# 🐱 KittenCareOS

![A playful kitten](https://wallpaperaccess.com/full/12458.jpg)

## Caring for your kitten

Bringing a kitten home is the start of a wonderful adventure, but it comes with real responsibility. Kittens thrive on routine — small, frequent meals of high-quality kitten food, a clean litter box, and a warm, safe space to sleep are the essentials. During their first year they grow rapidly, so an early vet visit is important to set up a vaccination schedule, check for parasites, and get tailored nutrition advice. Beyond the basics, kittens need daily play and gentle handling to build confidence and develop into well-socialised adult cats. A scratching post, a few toys, and plenty of your time are all they really ask for — in return, they'll reward you with a lifetime of companionship.

---

## About this project

KittenCareOS is an open-source platform for tracking kitten health, feeding schedules, vaccinations, and vet visits — built for foster carers, shelters, and cat families.

## Features

- 🏥 **Health tracking** — weight, vaccinations, deworming, and vet visits with reminders
- 🍼 **Feeding logs** — scheduled feeds, formula tracking for neonates, weight gain curves
- 👤 **Foster profiles** — multi-kitten management, litter grouping, and adoption status
- 🔔 **Reminders** — push and email alerts for vaccines, medications, and feeding windows

## Getting started

```bash
git clone https://github.com/purrfect-org/kitten-care-os
cd kitten-care-os
cp .env.example .env
pnpm install && pnpm dev
```

## Project structure

```
kitten-care-os/
├── apps/
│   ├── web/         ← Next.js dashboard
│   └── mobile/      ← React Native carer app
├── packages/
│   ├── api/         ← Hono REST + tRPC
│   ├── db/          ← Drizzle ORM + Postgres
│   └── shared/      ← Types, utils, schemas
└── docs/            ← ADRs, API reference
```

## Contributing

We welcome contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or submitting changes. Use the issue templates in `.github/ISSUE_TEMPLATE/` to report bugs, request features, or flag medical data concerns.

## License

MIT © purrfect-org
