# Demos and templates for rs - the Racket Sequencer

## Overview

This repository contains demo files and templates (well, one template) to show how the live MIDI coding tool rs (Racket Sequencer) works.

For more info on rs go to https://github.com/mcdejonge/rs

rs can also be found in the Racket package catalog.

rs is a set of files / library for doing live coding of MIDI sequencing using the [Racket](https://racket-lang.org) programming language. Since Racket is a type of Lisp, sequencing in rs is done by creating lists of events and looping them.

### Files

* **rs-demo1** The simplest possible notes. Plays a few notes on a monophonic instrument. Use this to check if everything works on your system.
* **rs-demo-chords** Shows how you can play chords.
* **rs-demo-drums** Shows how you can play drum sequences using Ableton drum racks (this is basically just playing notes, though).
* **rs-demo-polymeter** Shows how you can use polymeter, ie playing two loops simultaneously of the same length but each with a different number of steps.
* **rs-demo-polyrhythm** Shows how you can use polyrhythm, by playing two loops simultaneously that each have a different number of steps AND a different length.
* **rs-diag-timing** A simple script you can use to verify timing performance on your system.
* **rs-live-template** A starting template for your own experiments in live coding with rs.
* **rs-tool-cc** A tool for setting up your DAW / your MIDI instrument to listen to specific MIDI CC numbers.
