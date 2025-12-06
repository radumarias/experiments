# LLM Git conflict resolve

A more and more prominent issue with all these AI coding agents is that we tend to have more code we don't fully understand, and when we are working in a team, it's inevitable to make changes to the same file/code and to have git merge conflicts.  
And given that the conflicted code was most likely not written by us, resolving such merge conflicts could be hard and not a pleasant job for a dev.

So we are experimenting with how AI agents could help mitigate this. After all, they will be the ones writing that code :)

One idea is to use Claude Code skills to instruct the agent how it could help like
- instructions on steps that would help, something similar to https://subagents.cc/
- analyze previous commits to see how the code evolved
- include in the skill any code that might help to be executed while investigating
- ... open to suggestions
