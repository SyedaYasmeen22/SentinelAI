# SentinelAI

A minimal browser-based application for running a model and displaying detection results.

## Overview

This repository contains a single HTML file that loads the model, runs detection, displays statistics, and maintains a log.

## Usage

1. Open `\.html` in a modern browser.
2. Allow camera access if prompted.
3. The page will start running the model and update the dashboard.

## Fix

- Corrected the log update code so it safely checks the first log row using `firstElementChild`.

## Notes

- If the app reports a model failure, refresh the page and ensure the browser supports the required APIs.
- This repository currently contains only the HTML application file.
