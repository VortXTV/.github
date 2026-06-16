<p align="center">
  <img src="https://raw.githubusercontent.com/VortXTV/VortX/main/docs/brand/social-preview.png" width="640" alt="VortX">
</p>

<p align="center">
  <strong>Everything. VortXed.</strong><br>
  The native streaming client for Apple devices. Video, Audio, and Live TV, on every screen.
</p>

---

**VortX** (formerly StremioX) is a fully native streaming client for **Apple TV, iPhone, iPad, and Mac**, built on [stremio-core](https://github.com/Stremio/stremio-core) (the same Rust engine the official apps use) and a real **libmpv** player, with no web wrapper. It picks up where Stremio's Apple apps stalled and carries them forward. More platforms (Android, Windows, Linux) are on the way on the same shared engine.

### Apps

| App | Platforms | Status |
|---|---|---|
| **[VortX](https://github.com/VortXTV/VortX)** | Apple TV · iPhone · iPad · Mac | **Shipping** · [latest release](https://github.com/VortXTV/VortX/releases/latest) |
| Android | phone + TV | In development (in [VortX](https://github.com/VortXTV/VortX), `android/`) |
| Desktop | Windows · Linux · Mac | In development (in [VortX](https://github.com/VortXTV/VortX), `desktop/`) |

Everything lives in the one **VortX** repo today (the Apple apps are shipping; the others are maturing on the same shared engine). As VortX grows, each platform gets its own repo here in the org.

### What you get
- Native SwiftUI on every Apple screen, no web wrapper.
- The same open-source Rust engine (stremio-core) the official apps run on.
- A real libmpv player: HDR and Dolby Vision tonemapping, full audio, subtitle, and quality control.
- You bring your own account, add-ons, and sources. VortX hosts no content and bundles none.

### Get it
Download the latest sideload IPA (Apple TV / iPhone / iPad) or the Mac `.dmg` from **[Releases](https://github.com/VortXTV/VortX/releases/latest)**. Setup guides: [Apple TV, iPhone, iPad](https://github.com/VortXTV/VortX/wiki/Installing) and [Mac](https://github.com/VortXTV/VortX/wiki/Install-on-Mac).

### Roadmap

- **Now:** native Apple apps on stremio-core and libmpv, shipping with in-place updates.
- **Next (0.4):** native debrid, a richer Home, in-app add-on install, a Dolby Vision playback path, and the Android and desktop builds maturing.
- **Later (toward 1.0):** VortX's own engine, streaming server, ranking, and metadata, plus more platforms.

Full plan in the [roadmap](https://github.com/VortXTV/VortX/blob/main/ROADMAP.md); shipped changes in the [changelog](https://github.com/VortXTV/VortX/blob/main/CHANGELOG.md).

### Community
- Bugs and feature requests: [Issues](https://github.com/VortXTV/VortX/issues)
- Ideas and questions: [Discussions](https://github.com/VortXTV/VortX/discussions)
- Website, Discord, and subreddit: coming soon.

### Built with
Swift · SwiftUI · stremio-core (Rust) · libmpv via MPVKit · nodejs-mobile

<sub>An independent, open-source community project (GPL-3.0). Not affiliated with or endorsed by Stremio, Apple, or Anthropic. All names and trademarks belong to their owners. See each repository's Legal and DMCA notice and License.</sub>
