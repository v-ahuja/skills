# Skills

A small collection of reusable skills for coding agents.

## Install

Install a specific skill with the [`skills`](https://www.skills.sh/docs/cli) CLI. From the project where you want to use it, run:

```sh
npx skills add v-ahuja/skills --skill pr-walkthrough
```

The CLI will guide you through choosing the agent and install location. Add `--global` to make the skill available across your projects, or use `--agent codex` to target Codex directly.

## Available skills

### `pr-walkthrough`

Helps you build a clear mental model of a pull request by inspecting its real diff and relevant base code, organizing the change into coherent slices, and explaining one small diff excerpt at a time. Use it when you want to understand, trace, chunk, or walk through a PR.
