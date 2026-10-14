# Security

This repository holds documentation, one skill procedure, and one static page. It runs no service and stores no
data. Credentials, addresses, and machine details are kept outside it, in local-only locations.

## What it holds

- Generic descriptions of a working method.
- A generic dashboard skill procedure with no tools and no output.
- Example checklists and an example table with fictional repositories.
- A static page with inline example content and no scripts that call out.

## What it never holds

- Credentials, tokens, keys, or environment files with real values.
- Private addresses, host names, local paths, or personal usernames.
- Container, network, firewall, host, or monitoring configuration.
- Sweep output, session notes, work diaries, change logs, or lists of unfinished work.
- Backups, caches, editor folders, or exported runtime data.

The repository's ignore file blocks these by generic pattern, as a second check.

## Accepted risks

This site has no input, no server side, and no third-party scripts, so its exposure is limited to the text it
publishes. Review anything you add against the list above.

## Reporting

Report security problems privately to the repository owner, not in a public issue.

## Pre-commit checklist

1. Review the staged diff and read every line.
2. Scan staged content for secret-like values. Any match must be a placeholder.
3. Confirm no environment file with real values is staged.
4. Confirm no private addresses, machine names, usernames, or local paths are staged.
5. Confirm no logs, notes, sweep output, or runtime data are staged.
6. Confirm no empty files are staged.
7. Confirm the page loads no external script, font, or tracker.
