# capability-random-bytes

Atomic authority package for `random/bytes`.

- imports: `#{:random-bytes}`
- effects: `#{:randomness}`
- default policy: `:autonomous`
- semantic definition CID: `bafyreidauidawvzfmrbe2wi2dn62flk2sejjpfp6omszbvhwjqfeslk7ai`
- hash contract CID: `bafkreiflhj3fslsbh7okdas2fzlhmogai64x6p3lkla6gtr7berbp7ftvi`
- provider status: `contract-only`

The repository name is a discovery alias. The semantic definition CID
is the immutable import identity. Importing it does not grant runtime
authority: Tamaki must request it explicitly and Kototama must admit
the sealed envelope.

```sh
clojure -M:test
```
