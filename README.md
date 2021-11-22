# Pecha Kucha

Pecha Kucha is a presentation format for quickly getting ideas to your audience.
It is constrained to 20 slides with 20 seconds foe each slide.

## Presentation

This presentation follows this script:

- My introduction and how I came to be here.
- What is computer science?
- What is computer vision?
- Working with faces.
- Presenting tips.

## Building

The content is written in `Markdown` and converted using `pandoc`.
The slides are built using the Makefile in the lecture directory.
There is a corresponding Makefile in the labs directory.

I use some templates and defaults available at:

    https://github.com/uea-teaching/teaching-slides

I prefer to use Docker to run Pandoc, again the repo above has a Dockerfile.
There is also a Makefile in the root of this repo if you already have Docker installed.

## Slides

The slides can be built without auto-advance by removing:

    -V autoSlide=20000 \

from the Makefile.
