# Setup

## Anti-Gravity

Open this project as the workspace root.

Use `master prompt.md` as the orchestration prompt.

## First episode

Put chapters in:

`episodes/EP001/chapters/`

Then run Cold Mode.

## Next episode

Copy:

`_EPISODE_TEMPLATE/`

to:

`episodes/EP002/`

Rename the folder to the desired episode number.

Then put the next source chapters into that new folder.

The master prompt will use the existing `series/` state to maintain continuity.

## GitHub

Recommended commits:

- `EP001 production complete`
- `EP002 production complete`
- `EP003 production complete`

Do not commit generated raw audio/video unless you intentionally want them in Git.
Use Git LFS or Google Drive for large media.
