# LEXOLA — release manifest

Public distribution point for the **LEXOLA SketchUp extension**. The source repo is private;
this repo carries only the update manifest and the release archives, so the extension's own
update check can fetch them anonymously without shipping a token to every user.

- `latest.json` — polled by `lexola_ext/updater.rb` (`MANIFEST_URL`)
- archives — attached to the GitHub Releases of this repo

Install: download the `.rbz` and use SketchUp's **Extension Manager → Install Extension**.
