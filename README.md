<div align="center">

<a href="#novu-london--high-fashion-novus">
  <img src="assets/novu-readme-scene.svg" alt="Animated Novu London scene with a rotating 3D cube" width="100%">
</a>

<h1>Novu® London — High-Fashion Novus</h1>

<strong>AN INTERACTIVE DIGITAL FASHION EXPERIENCE</strong>
<br><br>
<strong>✦ MADE BY KAMLESH SINGH KOTWAL ✦</strong>
<br><br>

[Explore the experience](#experience) · [Run locally](#run-locally) · [Publish on GitHub Pages](#publish-with-github-pages)

</div>

> **Live visual:** the banner above is a locally hosted animated SVG—no external image service or JavaScript is needed to show it. GitHub sanitizes custom README scripts and CSS, so the README uses SVG motion and native disclosure controls for its live elements.

## ✦ Experience

| ◈ Motion | ◉ Explore | ◌ Discover |
|:--|:--|:--|
| Scroll-linked character scenes, animated typography, and cinematic transitions. | Drag or swipe through the partner carousel; point at cards on desktop for a 3D tilt and light effect. | Tap the spinning cube in the page controls to jump to a randomly selected partner. |

<details>
<summary><strong>＋ More interactive details</strong></summary>
<br>

- **The Drop:** A full-screen editorial hero with animated lettering.
- **The Walk:** Story panels change as you move through the page.
- **Partner carousel:** Drag, swipe, or let the cards drift; the progress indicator follows along.
- **Navigation:** Open the full-screen menu, use the page controls, or press <kbd>Space</kbd> to move between sections.
- **Motion preferences:** Reduced-motion settings use a calmer, still-image presentation.

</details>

<details>
<summary><strong>＋ See the 3D cube artwork</strong></summary>
<br>

<div align="center">
  <img src="assets/novu-readme-scene.svg" alt="Isometric cube with orbiting rings and animated highlights" width="360">
  <br>
  <em>Hover and scroll interactions are part of the webpage; this illustration animates in compatible SVG viewers.</em>
</div>

</details>

## ◈ Run locally

No build step or package installation is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser, or serve the project folder with any static web server.
3. For the most reliable experience, use a local server (for example, VS Code Live Server). Some browsers restrict media and worker features when an HTML file is opened directly.

## ◉ Publish with GitHub Pages

1. Push `index.html`, `README.md`, and the `assets` folder to the root of your GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, choose the desired branch and the `/ (root)` folder, then save.
4. Open the published URL shown on the Pages settings screen.

## ◌ Browser and asset notes

The desktop scene uses WebCodecs, workers, and an MP4 parser when the browser supports them. It falls back to video-frame capture if that pipeline is unavailable. Mobile and reduced-motion modes use still images instead. The visual media and web fonts are loaded from external URLs, so those assets require an internet connection and continued availability of their hosts.

## Credits

**Designed, built, and made by Kamlesh Singh Kotwal.**
