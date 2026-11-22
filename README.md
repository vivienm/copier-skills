# Skills project template

An opinionated [Copier] template for [Agent Skills] projects.

Generated projects include a root-level skill directory, a README that lists the
skills, and Markdown formatting instructions in `AGENTS.md`. Selecting `github`
as the forge adds a GitHub Actions workflow that checks Markdown formatting and
validates the skills.

## Quickstart

First, [install Copier][copier-install].

To create a project, run Copier and answer the prompts:

```bash
copier copy 'https://github.com/vivienm/copier-skills' path/to/your/project
```

Then enter the generated project and initialize its Git repository:

```bash
cd path/to/your/project
git init -b main
```

Replace the `do-something` example with your own skill and update the list in
`README.md`. With [npm] installed, format the Markdown files:

```bash
npx --yes prettier --write --prose-wrap always --print-width 80 '**/*.md'
```

Commit your project files. To update the project later, run the following from a
clean working tree:

```bash
copier update --skip-answered
```

[Copier]: https://copier.readthedocs.io/en/stable/
[Agent Skills]: https://agentskills.io/
[copier-install]: https://copier.readthedocs.io/en/stable/#installation
[npm]: https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
