<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
    <img src="assets/header-light.svg" alt="Prometheion" width="412">
  </picture>
</p>

Prometheion is a shared home for open-source projects in the local AI movement: people who run AI on their own computers instead of renting it from a cloud service.

## The name

The name means a shrine of Prometheus, who in Greek myth stole fire from the gods and gave it to people. Pausanias, a Greek travel writer of the 2nd century AD, describes an altar of Prometheus in the Academy outside Athens. A torch race started at that altar and ran to the city, and a runner whose torch went out could not win (*Description of Greece* 1.30.2).

## What we build for

Most AI tools today run on a company's servers, so your prompts and files go to that company. The projects here run on your own computer instead.

- Privacy: your data stays on your machine. Nothing goes to a cloud service unless you set that up yourself.
- Ownership: you choose what runs, you can read the code to see what it does, and you can remove any part of it.
- Modest hardware: a project should work on a normal home computer, such as one with an 8 GB graphics card and 32 GB of RAM.

## Projects

| Project | What it is |
|---|---|
| [Pithagoras](https://github.com/thecodacus/pithagoras) | A self-hosted web portal for the [pi](https://pi.dev) coding agent, with extensions, voice mode and chat modes. A task keeps running on the server after you close the browser. [Docs](https://thecodacus.github.io/pithagoras/) |
| [Pithagoras Flair](https://github.com/prometheion/pithagoras-flair) | Cosmetic and opinionated extensions for Pithagoras. A 3D VRM avatar for voice mode is in progress. |
| [Pithagoras Extensions](https://github.com/prometheion/pithagoras-extensions) | A collection of extensions for Pithagoras, started by Piggidragon. Blender and Godot, each in a container for the agent to use, are in progress. |
| [Nerve Protocol](https://github.com/prometheion/nerve-protocol) | An MCP server that lets an agent read and write files and run commands on its owner's machines. On each machine the owner decides what is allowed, and everything else is refused. |
| [Understory](https://github.com/thecodacus/understory) | Memory for AI agents, kept as plain Markdown files that an LLM writes, links together and keeps in order. It works with local models. |

Pithagoras and Understory are under the thecodacus account for now.

## Join in

- To report a bug or ask a question, open an issue in the project's repository. Pull requests are welcome in every project.
- To propose a new project, open an issue in [prometheion/.github](https://github.com/prometheion/.github). Say what it does, what hardware it needs, and how it keeps data on the user's machine.
- Members: [thecodacus](https://github.com/thecodacus) and [Piggidragon](https://github.com/Piggidragon).
