# React and Redux note-taking — source study

These notes were added in October 2026. The application is the work of the original upstream contributors. This fork does not claim the upstream code, dates, or experience as work by Ruth Ramos.

Source: [taniarascia/takenote](https://github.com/taniarascia/takenote). The exact imported revision is recorded in [SOURCE.json](SOURCE.json).

## Source map

| Entry point | What to trace |
| --- | --- |
| [src/client/slices/note.ts](../src/client/slices/note.ts) | Note state and reducer operations |
| [src/client/slices/category.ts](../src/client/slices/category.ts) | Category state |
| [src/client/containers/NoteEditor.tsx](../src/client/containers/NoteEditor.tsx) | Editor container |
| [src/client/index.tsx](../src/client/index.tsx) | Client entry point |
| [src/server](../src/server) | Optional Express server implementation |
| [CONTRIBUTING.md](../CONTRIBUTING.md) | Folder structure and test commands |

## Study exercise

Compare the documented browser-only demo with the optional self-hosted server. Trace a note edit from the editor into Redux and the available persistence/sync paths.

## Setup and verification

Use the preserved [upstream README](../README.md) for setup and the repository package scripts for the exact commands. This addition changes documentation only. Dependencies were not installed and application tests were not run.

The added documentation was checked for valid local links, a matching upstream revision, unchanged application files, and preservation of the [MIT license](../LICENSE).

## Attribution

The original license and copyright notice remain unchanged. All imported commits retain their original authors. Only this fork's study documentation is a new contribution dated October 2026.
