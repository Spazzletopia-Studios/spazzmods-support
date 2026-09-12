# How SpazzMods support works

## Where to post

| You have | Use |
| --- | --- |
| A module that misbehaves | [Bug report](https://github.com/Spazzletopia-Studios/spazzmods-support/issues/new?template=bug.yml) |
| A download, an install, or an update that fails | [Install or download problem](https://github.com/Spazzletopia-Studios/spazzmods-support/issues/new?template=install.yml) |
| A "how do I" question | [Question](https://github.com/Spazzletopia-Studios/spazzmods-support/issues/new?template=question.yml) |
| An idea or a request | [Idea](https://github.com/Spazzletopia-Studios/spazzmods-support/issues/new?template=idea.yml) |
| Anything about money, membership, or your personal details | A [Patreon](https://www.patreon.com/c/SpazzletopiaStudios) message, never a public issue |

## What happens after you post

1. **Sorted.** Every new issue gets a priority label. That happens on Mondays,
   and the same day for a P0.
2. **Reproduced.** We try to make it happen here. If we cannot, we ask for the
   missing piece and label the issue `needs-info`. An issue with no answer for
   14 days is closed, and you can reopen it whenever you come back to it.
3. **Fixed and released.** The fix goes out in a numbered release. An issue is
   closed when the version carrying the fix is public, not when the code is
   written, and the closing comment names that version.

Releases go out on Fridays. A P0 fix goes out the moment it is ready.

## Priorities

| Priority | What it means | Examples |
| --- | --- | --- |
| **P0** | Data loss, a security problem, or the catalog and downloads are out | A module deletes items from a character; a download fails for everyone |
| **P1** | A main feature is broken, or a Pathfinder rule gives the wrong result | A check uses the wrong DC; a window will not open |
| **P2** | An edge case, or something looks wrong | A misaligned panel; a rare combination of options misbehaves |
| **P3** | An idea or a request | A new option; support for another module |

## What makes a report easy to fix

- The module name and its version, and your Foundry and Pathfinder 2e versions.
- The exact steps. "Open the board, pick Forage, click Roll" beats "it broke".
- What you expected, and what happened instead.
- The console error. Press **F12** in Foundry, open **Console**, and copy the
  red text. Screenshots of the error are fine too.
- Whether it still happens with only the one SpazzMods module enabled.

## What we cannot do

- Support Foundry or Pathfinder 2e versions outside the tested range.
- Fix a defect inside another author's module. We will help you identify it and,
  where we can, work around it on our side.
- Give Supporter module files to anyone who is not a supporter, or help with
  copies taken from elsewhere.

## Conduct

Be decent to whoever reads your issue. Disagreement is fine, personal attacks
are not. Do not paste Paizo's published text into an issue; describe the rule
and name it instead.

Issues that break this are closed.
