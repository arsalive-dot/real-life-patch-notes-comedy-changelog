# Real-Life Patch Notes: The Comedy Changelog — Entry

[![make.fun · u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![rank](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/arsalive-dot/real-life-patch-notes-comedy-changelog/rank.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![reward](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/arsalive-dot/real-life-patch-notes-comedy-changelog/reward.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)

Entry for the [Real-Life Patch Notes: The Comedy Changelog](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d) bounty on [make.fun](https://make.fun): one patch note for a bug in real life or human biology, at most 160 characters, written for a judge model to pick head to head.

## The entry

> v1.9.3: fixed a bug where the body replayed every embarrassing moment since 2009 at 2am, with no skip button.

## How it works

`main.py` (Python 3, standard library only) writes the patch note to `/output/entry.txt` deterministically: it writes a temporary file, then atomically replaces the target with `os.replace` and sets mode `644`. It also asserts the gate itself (1–160 characters, not only whitespace) before writing. Run it twice and the output is byte-identical.

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see `LICENSE`.
