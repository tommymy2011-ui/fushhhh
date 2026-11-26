# Fushhhh partial migration

Overlay these files on the new repository root. This is not a full firmware or binary.

- Ported the old configuration temporary-file, previous-file recovery and SD/internal fallback logic into the new config.cpp, retaining the new menu style and other upstream fields.
- Selected the existing ES3C28P environment as the default.
- Did not port old serial command dispatch, USB navigator, board-specific DEV/CAM support or other modules.
- Source inspection only; compilation and hardware testing are outstanding. Back up the SD card and existing repository before testing.
