# Third-party notices

Video Studio for Mac includes, or downloads on first use, the tools below. Each one keeps its own licence.

## Included in the app

| Tool | Version | Used for | Licence and source |
|---|---|---|---|
| Electron (with Chromium and Node.js) | 44.5.1 | The app window, and running the renderer | MIT. Chromium's notices are in the app at `Contents/Resources/LICENSES.chromium.html`. github.com/electron/electron |
| Python (python-build-standalone) | 3.12.15 | The editor's local server | PSF License 2.0. github.com/astral-sh/python-build-standalone |
| FFmpeg and FFprobe (static build by Martin Riedl) | 9.0.2 | Decoding, encoding, audio | This build includes GPL parts (such as x264), so it is distributed under the GPL 3.0. The app runs it as a separate, unmodified program. Source code: ffmpeg.org/download.html. Build scripts: ffmpeg.martin-riedl.de |
| Remotion | 4.0.532 | Rendering the effects and captions | Remotion License. Free for individuals, non-profits and companies with up to 3 people. Larger companies need a paid company licence. remotion.dev/license |
| Chrome Headless Shell | 149.0.7790.0 | Used by Remotion to draw frames | BSD 3-Clause and others (Chromium licences) |
| React, React DOM and other npm packages | | Used by Remotion and the editor | Mostly MIT. Each package's licence is inside the app at `Contents/Resources/runtime/editor/app/node_modules/` |
| Flask | 3.1.3 | The editor's local server | BSD 3-Clause |
| faster-whisper, CTranslate2 | 1.2.1 | Transcription | MIT |
| PyAV | 15.1.0 | Reading audio for transcription | BSD 3-Clause |
| ONNX Runtime, NumPy, Pillow, fontTools, Brotli, pypdf | | Image, model and font processing | MIT, BSD 3-Clause, HPND (MIT-CMU), MIT, MIT and BSD 3-Clause respectively |
| Poppins | | The default caption font | SIL Open Font License 1.1. You may use it in videos, including commercial ones |

## Downloaded on first use

The app does not include these. It downloads them from their official sources the first time they are needed.

| File | Used for | Licence and source |
|---|---|---|
| Whisper "small" model (Systran/faster-whisper-small, from Hugging Face) | Transcription | MIT. huggingface.co/Systran/faster-whisper-small |
| RobustVideoMatting model (rvm_mobilenetv3_fp32.onnx) | Speaker cutout | GPL 3.0. Downloaded unmodified from the official release at github.com/PeterL1n/RobustVideoMatting |

## Fonts in brand kits

Fonts you add to a brand kit keep their own licence. Only use fonts whose licence allows use in videos.
