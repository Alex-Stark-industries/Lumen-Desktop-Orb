# Third-party notices

Lumen is built with the following open-source components. This file exists
to satisfy their attribution/notice requirements.

## sharp / libvips — LGPL-3.0-or-later AND Apache-2.0

Lumen bundles `sharp` (an optional dependency of `@huggingface/transformers`,
which Lumen uses only for on-device voice synthesis — sharp's own image-
processing features are never invoked). sharp wraps libvips, licensed under
LGPL-3.0-or-later. Per the LGPL, this notice is provided, the license text is
reproduced below, and the component is loaded as a separate, independently
replaceable native module (`node_modules/@img/sharp-win32-x64`) rather than
compiled into Lumen's own code.

- Project: https://github.com/lovell/sharp
- License text: https://github.com/lovell/sharp/blob/main/LICENSE
  (Apache-2.0 for sharp's own JS code; libvips itself is LGPL-3.0-or-later —
  https://github.com/libvips/libvips/blob/master/COPYING)

## @huggingface/transformers — Apache-2.0

https://github.com/huggingface/transformers.js

## kokoro-js — Apache-2.0

The local neural voice engine. https://github.com/hexgrad/kokoro

## Electron — MIT

https://github.com/electron/electron

---

All other dependencies (development tooling, build-time only) are under
permissive MIT/ISC/BSD/Apache-2.0 licenses and are not distributed inside
the packaged application.
