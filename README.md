# Overview
This repo is an exploration of how a repo `README.md` and a `CLAUDE.md` can live together and share common sections while keeping things dry and minimizing the need to update multiple files when new shared content is created.
Another goal is to keep the addition of context to the LLM as small as possible.

The approach demonstrated here is to maintain common sections in `CLAUDE.md` and then link to them from `README.md` ensuring that only information that is explicitly meant for Claude is included as context.  An alternative approach would be to use a more formal docs directory with separate markdown file for each common topic.  The main objections to this approach are that it can be overkill for simple projects and requires:

1. create the new snippet file
2. link to the snippet in `CLAUDE.md` 
3. link to the snippet in `README.md`

 as opposed to: 

1. add the section to `CLAUDE.md`
2. link to the new section in `README.md`

# Coding Conventions
See [Coding Conventions](./CLAUDE.md#coding-conventions)

# Design Patterns
See [Design Patterns](./CLAUDE.md#design-patterns)
