# Meta Robots Tag Helper

This tool builds a meta robots tag and the matching X-Robots-Tag header by toggling crawl and index directives. The meta tag goes in the head of an HTML page; the header does the same job for non-HTML files like PDFs, set at the server.

**Live demo:** https://0xelitesystem.github.io/meta-robots-tag-helper/

## What it does

Toggle index or noindex, follow or nofollow, and extra restrictions like noarchive, nosnippet, noimageindex, and notranslate, then set max-snippet and max-image-preview if you need them. The tool writes both the HTML meta tag and the X-Robots-Tag header, and warns when noindex is set or when the result is just the default.

noindex tells engines to drop the page from results; nofollow tells them not to pass signals through its links. This pairs with the robots and llms.txt generator and the security-headers reference.

## Aesthetic

An industrial stencil placard: a crate-board panel with stencilled directives, safety-yellow accents, and the two outputs printed below a heavy rule.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
