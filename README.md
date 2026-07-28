# capability-random-bytes

Atomic authority package for `random/bytes`.

- imports: `#{:random-bytes}`
- effects: `#{:randomness}`
- default policy: `:autonomous`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
