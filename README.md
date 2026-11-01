# Probe Garden

An interactive outreach demo for the paper **"Rewilding Natural Intelligence: The Case for a Conservative Approach in Introducing AI into Space"** by Soumya Banerjee (University of York).

**[Live demo:**](https://neelsoumya.github.io/probe-garden) `https://neelsoumya.github.io/probe-garden/`

## Central thesis

Space is a place where errors are irreversible and communication is slow, so the AI we send there should be designed for humility, stewardship and minimal impact. The paper argues for a categorical ban on autonomous self-replication, while allowing tightly bounded self-repair, with human oversight of high-consequence actions, a strict duty to do no harm and not interfere with extraterrestrial environments, and institutional safeguards such as mission certification and an international Space AI Safety Institute.

## What the simulation shows

Robot probes spread through a patch of stars, some of which host fragile life. You can:

- let probes copy themselves, or restrict to a single non-copying probe with self-repair;
- protect or ignore living worlds;
- send a "STOP" signal from Earth at light speed.

Copies can drift from their original rules, and drifted probes ignore the STOP signal. It is a toy model meant to make the argument intuitive, not a prediction.

## Files

- `index.html`: landing page with the thesis and a link to the demo
- `simulation.html`: the self-contained interactive page (no dependencies)
- `.nojekyll`: tells GitHub Pages to serve files as-is

## Publish on GitHub Pages

1. Create a new public repository named `probe-garden` and upload these files to the root.
2. Go to **Settings > Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
3. After a minute the site is live at `https://<your-username>.github.io/probe-garden/`.

## Citation

Banerjee, S. *Rewilding Natural Intelligence: The Case for a Conservative Approach in Introducing AI into Space.* (add venue/DOI when available)

## Licence

Code: MIT. Text: CC BY 4.0. (Change as you prefer.)
