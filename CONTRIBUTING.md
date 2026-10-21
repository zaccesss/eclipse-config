# Contributing

Thanks for taking an interest. Contributions are welcome: preference fixes, key binding
corrections, merge script fixes and guide improvements.

## What belongs here

- A wrong key or value in `prefs/`
- A key binding whose command or context id is wrong for a current Eclipse release
- A merge script bug: a line it drops, mangles or duplicates
- A workspace path or install command that is wrong for a platform
- Improvements to the guides

## What does not belong here

- A preference or plugin that only reflects one person's taste rather than something broadly
  useful, keep that in your own copy

## How to contribute

1. Fork the repository and create a branch named `fix/<short-description>` or
   `feat/<short-description>`.
2. Change values in `prefs/` only, never in a script.
3. Run the script against a copy of a real workspace, open Eclipse on it and confirm the change
   shows in the preferences.
4. Open a pull request with a clear title and a one-paragraph description of what changed and
   why. CI checks the fragments and runs the merge twice.

## Reporting bugs

Open an issue with your Eclipse version, platform and the merge script's output, what you expected
versus what happened.

More about me and my work: [isaacadjei.me](https://isaacadjei.me).
