# Contributing

Issues and focused pull requests are welcome. When reporting a problem, name the skill, describe the request that exposed it, and explain the observed behavior and expected result. Remove credentials, customer data, and other private information from examples.

For a pull request:

1. Keep the change scoped to the affected skill and its supporting files.
2. Explain the decision or behavior the change improves and any new dependency it introduces.
3. Keep `SKILL.md` links and `agents/openai.yaml` metadata consistent with the change.
4. If you change a bundled script, run it against a temporary example and report the result. For instruction changes, describe a representative request and the expected decision path.
5. Do not include private repository content, credentials, or copies of the source lesson documents.

These skills should preserve user decisions and authorization boundaries. A skill that can write files, call an external service, or change Git state must say when that action is permitted and when it should stop.
