# FUSH OS branding and single-board build

Upload the contents of this patch at the repository root. The ES3C28P build exports only firmware.factory.bin. The upstream release matrix no longer runs on push or tags; do not manually dispatch that workflow if you only need ES3C28P. Other upstream workflows remain unchanged. Cancel any already-running unwanted matrix jobs separately.

Boot splash, local mDNS name, selected visible labels and default colors updated. Existing saved themes, boot media and custom WebUI assets can override these defaults. Existing config files, credentials, upstream credit links, and partition layout are unchanged. No compilation or hardware testing performed.
