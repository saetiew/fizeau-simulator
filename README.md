# Fizeau Bench 2″ — Simulator

**Live demo:** https://saetiew.github.io/fizeau-simulator/
**Source:** [`index.html`](index.html) (a single file with no build step)

This is an interactive browser simulator for a 2-inch Fizeau interferometer that tests flat optics.

Optical layout: HeNe 632.8 nm → L1 (asphere) + pinhole → beamsplitter → L2 (Ø2″ collimator) → reference flat (Thorlabs WW42012-A) → sample.

## Features

- To-scale system diagram with live beam-expander calculations: magnification, beam diameter, edge intensity, and ghost offset
- Simulated camera fringes using a multiple-beam (Airy) cavity model
- Phase-shifting interferometry with Hariharan 5-step or 4-step algorithms, plus phase-error maps

## Run locally

Download `index.html` and open it in any browser. It needs no installation.
