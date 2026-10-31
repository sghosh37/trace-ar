# Trace AR

Project an image onto any surface in Meta Quest passthrough and trace it.

Open on the headset: **https://sghosh37.github.io/trace-ar/** (Meta Quest Browser), then install it from the browser so it appears in your App Library.

- **Choose an image** → it opens floating in front of you. Hold the trigger to carry it, *Lay flat* to put it on a table, *Lock* to trace.
- **Start tracing** → select a surface first (Lasso, Sweep, Detect, Quick flat), then the image is projected onto it.
- **Lock** freezes the image in place; Raise / Lower and the move buttons still fine-tune it in 1 mm steps. Hold the button to unlock.
- **Save spot / Restore spot** (while locked): tap two marks on the desk; after the headset sleeps, tap them again to put the image back.
- Picked images are saved inside the app and appear in the in-headset **Image** gallery.

Single-file WebXR app (three.js). Works offline after the first visit.

## Design

The full feature-by-feature design, including how a locked image is kept in place through headset sleep, is in [docs/design.html](docs/design.html) — online at **https://sghosh37.github.io/trace-ar/docs/design.html**.

## License

Copyright (C) 2026 Suman Ghosh

Trace AR is free software: you can redistribute it and/or modify it under the terms of the **GNU General Public License v3.0** (or, at your option, any later version), as published by the Free Software Foundation. It is distributed WITHOUT ANY WARRANTY. See [LICENSE](LICENSE) for the full text.

Third-party code: [three.js](https://threejs.org/) (MIT License) is loaded from the jsDelivr CDN at run time and is not part of this repository.
