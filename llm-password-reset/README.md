# Semantic Zero-Knowledge-Like Proof

Proposing a move from Syntactic Authentication (exact string matching) to Semantic Authentication (meaning-based matching).
This approach allows for "fuzzy" logic, where the user proves they possess specific memories or knowledge without having to act like a robot memorizing an exact, case-sensitive phrase.

Experiment on how we could use llms maybe with RAG and embeddings to handle the reset pass functionality with a secret question you set but instead of needed to write the word as an answer the setup would be like this
- when you define the secret question you would explain to an llm your answer like writing about an event in your life or information you want to have as answer
- then when you need to reset pass you could be shown the question of some hint and you would respond the same describing the answer but not necessary with the same wording or words order like when you defined it, but should be on the same like
- then llm compares the answer you defined before with the one you give now and confirm in percentage that you are actually the holder of the account

We can use https://platform.claude.com/docs/en/agent-sdk/overview

See more details https://gemini.google.com/share/f9a6075f22d1

[See Issue #4](https://github.com/xoriors/experimental/issues/4)
