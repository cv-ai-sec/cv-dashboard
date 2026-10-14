# User Guide

Day-to-day reference. The site is a set of static files with no service, database, or background process.

## Viewing

| Way | How |
|---|---|
| Locally | Open `index.html` in a browser |
| Hosted | Serve the repository root with any static file host |

## Using the skill

| What | Where |
|---|---|
| The procedure | `skill/dashboard/SKILL.md` |
| Install | Copy the `dashboard` folder into your agent's skills folder, then adapt the inputs table to your own tools |
| Run | Type `/dashboard` in your agent |

The skill is a procedure only. Write your own sweep and build tools, and keep their output out of this repository.

## Changing the content

| What | Where |
|---|---|
| Dashboard cards, tables, and checklists | `index.html` |
| Method detail | `docs/WORKFLOWS.md` |
| Rules for what may be published | `docs/SECURITY.md` |

The dashboard holds example content only. Keep it generic: no addresses, host names, local paths, dates of work,
real repository names, or lists of unfinished items.

## Start and stop

There is nothing to start or stop. A browser tab is the only process. No data is written, so there is no state to
corrupt on close.

## Before you publish a change

Follow the pre-commit checklist in [SECURITY.md](SECURITY.md#pre-commit-checklist) and run your own security check
over the folder. Then commit with a message that describes the content.
