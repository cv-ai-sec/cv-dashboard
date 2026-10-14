# cv-dashboard

A small public site and a procedure that show how a repository health dashboard works: a read-only sweep of a set of
repositories, a score for each, and a summary a person can read in a minute. The data on the page is generic example
content. It describes a method, not any particular setup.

Open [index.html](index.html) in a browser to see the dashboard, or serve the repository root as a static site.

Already looking at it and just need the day-to-day notes? See [docs/USER-GUIDE.md](docs/USER-GUIDE.md).

This dashboard goes with [cv-security-best-practice](https://github.com/cv-ai-sec/cv-security-best-practice). The
checks the sweep runs are the ones that repository describes.

## Learning use

This repository is for learning. You can give its public material to a coding agent, such as Claude Code, to help
you build your own version. Give the agent the public docs and your own configuration only. Keep real credentials
and addresses out of the agent's context. If you build your own version, consider setting up a secure, private way to
export any restricted files it needs.

## What it shows

- **A dashboard procedure.** [docs/DASHBOARD-PROCEDURE.md](docs/DASHBOARD-PROCEDURE.md) is a generic run:
  refresh, open, summarise, state the limits, name the next actions.
- **An example sweep.** A table of example repositories with a verdict, a hygiene score, and a completeness score.
- **A task loop.** Scope, plan, build, check, document.
- **A publish gate.** The checks that run before anything is committed or made public.
- **A public and private split.** What a public repository describes, and what stays on the local machine.
- **A runbook shape.** How a change that touches a repository and a live service is written down.

## Documentation

- [docs/DASHBOARD-PROCEDURE.md](docs/DASHBOARD-PROCEDURE.md): the dashboard procedure, step by step
- [docs/WORKFLOWS.md](docs/WORKFLOWS.md): the task loop, the publish gate, and the runbook shape
- [docs/USER-GUIDE.md](docs/USER-GUIDE.md): viewing, adapting, and using the procedure
- [docs/SECURITY.md](docs/SECURITY.md): what this repository holds, what it never holds, and the pre-commit checklist

## Secrets and addresses

This repository holds no credentials, addresses, host names, or local paths. Examples use placeholders such as
`<host address>` and `<project>`.
