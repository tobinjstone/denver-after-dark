# Denver After Dark

Live "where are we now" page for the unofficial late-night crew at What's Next, Denver, Thu Nov 12.

Site: https://tobinjstone.github.io/denver-after-dark/

## Running the night

Everything is driven by the Google Sheet "Denver After Dark (live)" (sharing must be *Anyone with the link → Viewer*).

- **Stops tab**: one row per stop. The lowest row not marked `next` is where we are now.
- Planning a move: add a row with status `next` (venue can be `TBA`). Arrived: clear `next`, fix the time.
- `note` shows under the venue name. `address` is the street address; Denver is added for maps and Uber.
- **Hide tab**: paste a chat message ID or a name to hide it for everyone. Open the site with `#host` to see IDs.

### Groups

- **Groups tab**: one row per group (`group`, `leader`, `phone`, `signal`, `note`). Empty = one big group.
- With groups, visitors pick a group (key-tag rack); each group gets its own location, check-ins and chat, plus an "Other groups" board and an Everyone chat.
- **Stops tab `group` column**: which group a stop is for. Blank = every group (shared start, final meetup).
- Direct link to a group: `?g=room-1` (group name, lowercase, dashes).
- Preview with sample groups: open the site with `#demo-groups`.

If the Sheet can't be reached, the site falls back to `data.json` in this repo.

Chat and check-ins use public ntfy.sh topics (see `CONFIG` in `index.html`).
