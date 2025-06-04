# 3DxDemos

This repository provides small Web demos for the 3Dconnexion **Spacemouse** using the
`3DconnexionJS` framework.

The samples require the 3DxWare 10 driver with the Navigation Library running on
the local machine (macOS 10.6.1+ or Windows 10.8.12+ as noted in the vendor
documentation). The pages should be served from an HTTP server. For a quick test
run:

```bash
python3 -m http.server 8000
```

and open `http://localhost:8000/index.html`.

The `index.html` page links to three small demonstrations:

- **Dial Knob** – rotate a simple knob using the Spacemouse twist gesture.
- **Webpage Scrolling** – scroll a tall page using Spacemouse translation.
- **Timeline Scrubber** – scrub and zoom a horizontal timeline similar to a
  video editor.

The original 3DconnexionJS samples are kept in `3DConnexionSamples/` for
reference.
