# Rules for working on this project

## Git
- Commits Claude makes are authored as Claude: `Claude <noreply@anthropic.com>` (GitHub links it to its `claude` account,
  so Claude shows among the contributors). They end with a co-author line for the owner under the project's GitHub
  identity: `Co-Authored-By: Xzpy909 <217505861+Xzpy909@users.noreply.github.com>`.
- Commits the owner makes are authored under the project's GitHub identity.
- Whatever the identity: never the owner's real name or personal e-mail.
- Never put session links (`Claude-Session: …` or any other link to a chat or session) in commits, pull requests or anything pushed.

## Privacy: nothing personal in the repository
Applies to code, comments, tests, commit messages, README.md and every other file that is committed or pushed.
- No private information about the owner: real name, personal e-mail, local folder paths, machine details.
- No real names from the owner's library or from real life: real titles (comics, manga, books, games, sets), authors, artists, circles, publishers, cosplayers or other real people.
  Use made-up names in tests, comments and examples ("Starfall", "Moonforge", "Mirelle"…), even when a bug was found on a real file.

## File names
- `docs/NAMING.md` is the naming baseline (Cosplay and manga). Parser changes must keep it working (`tests/test_naming_baseline.py`).

## Before pushing
Read through the diff for anything above.
