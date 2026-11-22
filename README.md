# Skills project template

An opinionated [Copier] template for [Agent Skills] projects.

Generated projects include a root-level skill directory, a README that lists the
skills, and Markdown formatting instructions in `AGENTS.md`. Selecting `github`
as the forge adds a GitHub Actions workflow that checks Markdown formatting and
validates the skills.

## Quickstart

First, [install Copier][copier-install].

From a local checkout of this template, run:

```bash
copier copy . path/to/your/project
```

Then enter the generated project and initialize its Git repository:

```bash
cd path/to/your/project
git init -b main
```

Replace the `do-something` example with your own skill and update the list in
`README.md`. With [Prettier] on your `PATH`, format the Markdown files:

```bash
prettier --write --prose-wrap always --print-width 80 '**/*.md'
```

If you generated the project from a Git checkout of this template, commit your
project files. Later, from a clean working tree, run:

```bash
copier update --skip-answered
```

[Copier]: https://copier.readthedocs.io/en/stable/
[Agent Skills]: https://agentskills.io/
[copier-install]: https://copier.readthedocs.io/en/stable/#installation
[Prettier]: https://prettier.io/docs/install
