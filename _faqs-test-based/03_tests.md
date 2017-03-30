---
# Question title. Plaintext only.
question: "How do you count tests?"
---
For GitHub projects, we count a test whenever you make a change to your dependencies on your default branch, and depending on your settings, whenever you create a pull request which changes those dependencies. For the Snyk CLI, we count each call to `snyk test` or `snyk monitor` as a test.
