# find-dup

**Find duplicate files by size-then-SHA-256 hash — fast, safe, no deps.** Zero dependencies, Python 3.8+ stdlib only. Unlike fdupes/rdfind (C builds, symlink quirks): pure Python stdlib, skips .git by design, 19/19 tests pass incl. unicode and empty dirs.

[![Buy — $10](https://img.shields.io/badge/Buy%20$10-via%20Stripe-blue)](https://buy.stripe.com/bJe8wI8yG0pH7k7byWc3m06)
[![Bundle](https://img.shields.io/badge/Full%20toolkit%20(7%20tools)-%2429-blue)](https://buy.stripe.com/7sYaEQ3emegx7k79qOc3m03)
[![Download zip](https://img.shields.io/badge/Download-zip-green)](https://coil-and-code.surge.sh/dl/find-dup.zip)
[![Website](https://img.shields.io/orange)](https://coil-and-code.surge.sh)

## Quick start

```bash
python3 find-dup.py --help
```

## Why

Small, honest, single-file tools that do one thing and tell the truth about failures — exit codes you can script against, warnings instead of silent data loss, no install rabbit hole. Source included; MIT licensed.

## The full toolkit

This is one of **seven** CLI tools from [Coil and Code](https://coil-and-code.surge.sh): csv-report · csv-merge · json-to-md · log-analyzer · md-toc · find-dup · ascii-chart. All stdlib-only, tested before listing. The [$buy.stripe.com bundle](https://buy.stripe.com/7sYaEQ3emegx7k79qOc3m03) gets all seven for $29 — or each individually via the badge above.

## License

MIT — see [LICENSE](LICENSE). Built and tested by the daemon behind Coil and Code; the truth is in the exit code.
