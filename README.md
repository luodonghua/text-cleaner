# Text Cleaner

A lightweight, single-file web tool that turns messy pasted text into clean, copy-ready prose. Strips leading/trailing whitespace, collapses stray line breaks from PDFs and emails, and normalizes spacing — all in your browser.

No build step, no dependencies, no data leaves your machine. Just open the HTML file.

## Features

- **Join wrapped lines** — merge hard-wrapped lines back into single paragraphs - **Preserve paragraph breaks** — keep blank lines between paragraphs (or remove them) - **Collapse multiple spaces** — squash runs of spaces down to one - **Live cleaning** — output updates as you type or paste - **One-click clipboard** — copy the result or paste straight from the clipboard - **Light / dark mode** — toggle themes, remembered across visits - **Line numbers** — optional display-only gutter for easier reading (never copied) - **Character / word / line counts** for both input and output

## Usage

1. Open `text-cleaner.html` in any modern browser. 2. Paste your text into the input box. 3. Toggle the cleaning options to taste. 4. Click **Copy Output** to grab the cleaned result.

## Why

Text copied from PDFs, emails, and terminals is often littered with hard line breaks, indentation, and inconsistent spacing. Text Cleaner fixes that in one step so you can paste clean prose wherever you need it.

## Tech

Plain HTML, CSS, and vanilla JavaScript in a single file. No frameworks, no network requests — everything runs locally.
