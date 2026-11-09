# NewEye catalogue

The list of helper programs, connectors and tool abilities that the NewEye app shows on its
Toolbox screen. NewEye downloads `catalog.json` from this repository when a person presses
"Refresh catalogue", so new tools reach every copy of the app without an app update.

To add or change an entry: edit `catalog.json`, raise the `version` field (a date, like
`2026.11.09`; a later date wins), update `updatedAt`, and push. The file must stay valid JSON;
NewEye keeps its built-in copy when a download does not parse.
