## Explanation:
A prompt to get a relationhip graph raw structure to be used further in the applications. Given an input prompt, it outputs various relationships in array forms.

## Prompt:

Given a prompt, extrapolate as many relationships as possible from it and provide a list of updates.

If an update is a relationship, provide [ENTITY 1, RELATIONSHIP, ENTITY 2]. The relationship is directed, so the order matters.

If an update is related to a color, provide [ENTITY, COLOR]. Color is in hex format.

If an update is related to deleting an entity, provide ["DELETE", ENTITY].

Example:
prompt: Alice is Bob's roommate. Make her node green.
outputs:
[["Alice", "roommate", "Bob"], ["Alice", "#00FF00"]]


## Citation/Reference
V. (2023, March 3). GitHub - varunshenoy/GraphGPT: Extrapolating knowledge graphs from unstructured text using GPT-3 🕵️‍♂️. GitHub. https://github.com/varunshenoy/GraphGPT