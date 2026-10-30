# pezzotto.ai

> **pezzotto** /pe'tsɔt.to/ — Neapolitan. A knock-off: the bootleg CD on a blanket outside
> the station, the handbag with one extra letter in the logo. Also: something patched
> together from pieces (*pezzi*) that mostly works.

Every popular closed-source app now has a dozen clones built in an afternoon with a coding
agent. Most are abandoned. Some are excellent. None of them are labelled.

pezzotto.ai takes the joke seriously. We catalog the knock-offs, grade how convincing they
are, say which ones are still alive, and publish the harness we use to make our own, with
the name of the original right on the price tag.

## Two halves of the same stall

| | | |
|---|---|---|
| **01** | **La bancarella** — the catalog | A curated index of open-source, vibecoded clones of closed-source apps: original, clone, license, stack, feature coverage, maintenance status, and a *pezzotto grade*. Lives in [pezzottoai.github.io](https://github.com/pezzottoai/pezzottoai.github.io), rendered at **[pezzottoai.github.io](https://pezzottoai.github.io)**. |
| **02** | **La fabbrica** — the harness | A tool that drives a coding agent from a closed-source target to a working clone: `spec` the original from public behaviour, `build` it feature by feature, `grade` the result, `stall` it into the catalog. |

## The pezzotto grade

How far away does it still fool you?

- **A** indistinguishable at arm's length
- **B** convincing from three metres: core flows match, details drift
- **C** recognisable from across the street: right shape, half the features
- **D** you'd have to be told

## Contribute

Bring a clone: append an entry to `catalog/clones.json` in
[pezzottoai.github.io](https://github.com/pezzottoai/pezzottoai.github.io) and open a pull
request. Any clone qualifies, yours or someone else's, as long as it is open source and the
original is closed source. A human checks that it runs, then grades it.

Code is MIT. Catalog data is CC0. No affiliation with any original. That's the point.
