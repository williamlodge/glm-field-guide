# GLM Field Guide

A black-and-white, searchable field manual for Zhipu and Z.ai GLM models. Presentation follows [William Lodge’s Termux Field Guide](https://williamlodge.github.io/termux-field-guide/).

## What it covers

- Model selection and benchmark interpretation
- Reddit, YouTube, Chinese community reports, and access limitations
- API and coding-agent configuration
- Coding, everyday work, and research workflows
- Local model memory, quantization, and runtime choices
- Costs, subscription quotas, caching, privacy, and model licenses
- Troubleshooting, a seven-day trial, and eight reusable prompts
- 55 linked source entries with evidence and access notes

## Open locally

Open index.html directly in a browser. The guide has inline CSS and JavaScript and does not load external fonts, scripts, images, or trackers. The HTML content works offline; outbound source links require internet access. The separate Markdown download requires GLM_Field_Guide.md to be kept beside index.html.

Alternatively, run:

```bash
python -m http.server 8080 --bind 127.0.0.1
```

Open http://127.0.0.1:8080. The page includes section search, a mobile contents drawer, active-section navigation, code/prompt copy buttons, and print styling. If clipboard access is blocked when opening a local file, a copy button selects the text for manual copying.

## GitHub Pages

Publish the repository root through Settings → Pages → Deploy from a branch → main → / (root). No build step is required. The .nojekyll file keeps this a plain static site. This project is an offline-readable HTML document, not an installable PWA.

## Files

- index.html — complete guide and presentation
- GLM_Field_Guide.md — editable research source
- README.md — usage and publishing notes
- LICENSE — presentation attribution and license
- .nojekyll — static GitHub Pages marker

## Research scope

Research date: October 12, 2026. The guide preserves distinctions between documented facts, vendor claims, firsthand reports, and recommendations. It does not claim an exhaustive crawl or independently reproduced GLM benchmark. Coverage limitations are listed in the source register, including partial video, Zhihu, Xiaohongshu, and WeChat access. Treat prices and availability as a dated snapshot.

## Attribution and license

The presentation is adapted from Termux Field Guide by William Lodge under CC BY 4.0. Changes include GLM-specific content, navigation, mobile layout, accessibility, search, copying, and print behavior. See LICENSE. Linked third-party material retains its own rights and is not relicensed by this repository.

## Updates

For corrections, include the affected section, exact model/provider/tool version, date, reproducible steps where relevant, and a primary source. Do not submit credentials or private prompts.

