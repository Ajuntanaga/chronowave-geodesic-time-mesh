# Geodesic time mesh — Module II

Standalone interactive extract of Module II, "Geodesic time mesh", from the Chronowave Dynamics Temporal Engine: a single-file compendium of 17 interactive modules about the author's temporal framework. The full compendium, its manual and its edit log are in [chronowave-compendium](https://github.com/Ajuntanaga/chronowave-compendium). The module's own heading on the page reads: "Proper time and coordinate time, beating against each other".

## Use it

Download or clone this repository, then open [`Module_II_Geodesic_Time_Mesh.html`](Module_II_Geodesic_Time_Mesh.html) from disk in a current browser (GitHub only shows its source). There is no build step and nothing to install. Math (KaTeX 0.16.9) and fonts load from cdnjs and Google Fonts, so equations and typography need a connection.

## Files

| File | What it is |
|---|---|
| [`Module_II_Geodesic_Time_Mesh.html`](Module_II_Geodesic_Time_Mesh.html) | The module: one page with the shared styles, this module's section and the script statements it needs. |
| [`Module_II_Manual.md`](Module_II_Manual.md) | This module's part of the compendium's plain-text manual (extracted from rev b90 and hand-patched, so it may lag the page). |

The other two files are this README and a `.gitignore`.

## Where it comes from

Made on 2026-11-24 from rev b91 of the compendium page (commit `fbeb5b8` of chronowave-compendium) by the scripts in the `tools/split` folder of that repository (added in later commits). The section markup, the styles and the script statements are copied from the page without change. What differs is the page title and description, a short header and footer line and the link to the manual.

## Checks and limits

- A scripted headless-Chromium test loaded the page, moved every slider and select, clicked every button, sent pointer and wheel events to every canvas and sent key events to the document: 84 actions (the count includes 38 fixed key and window events), 1 canvas, no uncaught exception and no console error. It is a smoke test: this extract was not compared with the original module for identical behaviour, and nothing here has had an independent review.
- The framework is the author's own and still in progress; Module XVII of the compendium (also a repository of its own, [chronowave-verdicts-and-rulings](https://github.com/Ajuntanaga/chronowave-verdicts-and-rulings)) carries the page's own verdicts and open rulings.
- No license: all rights are reserved by default, beyond viewing and forking on GitHub; a license is the author's decision.
