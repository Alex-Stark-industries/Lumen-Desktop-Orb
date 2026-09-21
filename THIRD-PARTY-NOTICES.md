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

## phonemizer.js — Apache-2.0, running eSpeak NG — GPL-3.0-or-later

kokoro-js uses `phonemizer` (https://github.com/xenova/phonemizer.js,
Apache-2.0) to convert text to phonemes before synthesis; phonemizer.js
itself embeds a WebAssembly build of eSpeak NG
(https://github.com/espeak-ng/espeak-ng, GPL-3.0-or-later) to do that
conversion.

To keep eSpeak NG's GPL-3.0 code genuinely separate from Lumen's own
proprietary code — rather than linked into the same process — Lumen runs it
in its own isolated child process (`phonemizer.worker.cjs`), communicating
only over stdio, the same arm's-length relationship as shelling out to any
other external GPL command-line tool. The unmodified eSpeak NG/phonemizer.js
build that process runs is distributed as-is inside this app; its
corresponding source is phonemizer.js's own public repository above, and
eSpeak NG's own source is at its repository above.

- phonemizer.js license: https://github.com/xenova/phonemizer.js/blob/main/LICENSE
- eSpeak NG license: https://github.com/espeak-ng/espeak-ng/blob/master/COPYING

## Electron — MIT

https://github.com/electron/electron

---

All other dependencies (development tooling, build-time only) are under
permissive MIT/ISC/BSD/Apache-2.0 licenses and are not distributed inside
the packaged application.
