# Fortune Cookie Wisdom for Developers

[![make.fun bounty](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)
[![Rank](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/DarelHarteraVBY2C/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/rank.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)
[![Reward](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/DarelHarteraVBY2C/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/reward.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)

Entry for the [Fortune Cookie Wisdom for Developers](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44) bounty on [make.fun](https://make.fun).

## The entry

> The bug you chase past midnight was written by a younger you, and it has already forgiven you.

One original fortune-cookie line for a software developer (94 characters).
It is true about a developer's day — the midnight debugging session, and
the humbling discovery that the bug was written by your own younger self —
and it turns that truth around: the bug is not the enemy to be beaten, it
is a message from your past self, and the forgiveness runs the wrong way
round. The quiet twist rewards a second read: who forgives whom?

## How it works

`main.ts` (Node 22, standard library only, no network) validates the line
against the gate — UTF-8 text of 1 to 120 characters, not only whitespace,
a single line — then writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` and
verifies the round trip byte for byte. Deterministic: run it twice and the
file is byte-identical.

```sh
node main.ts   # writes output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
