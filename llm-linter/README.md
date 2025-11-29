# LLM linter

Trying to see how an LLM can act as a static code analyzer similar to
- https://www.sonarsource.com/
- https://github.com/rust-lang/rust-clippy

## Approach

1. First we try to create some prompts to use as system prompts or slash commands or sub-agents in claude code for ex to analyze some basic concepts of code. [See Issue #3](https://github.com/username/repo/issues/3)
2. Then we can experiment to create some Claude Skills out of them, where we have more docs and maybe some code
3. Expose as MPC server
4. Integrate it in CI/CD with GitHub actions
5. Transform clippy rules to LLM prompts and enhance them
