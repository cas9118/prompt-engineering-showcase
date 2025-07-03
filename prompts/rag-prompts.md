# Retrieval-Augmented Generation (RAG) Prompts

## Example: Injecting Context
```
Use the following information to answer the question.
Context: [insert retrieved content]
Question: [user question]
Answer:
```

## Example: Multiple Source Merge
```
You have 3 documents on climate policy. Combine insights to answer:
[Doc1]
[Doc2]
[Doc3]
Question: How are these policies different?
```