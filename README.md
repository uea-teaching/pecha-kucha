# Pecha Kucha

Pecha Kucha is a presentation format for quickly getting ideas to your audience.
It is constrained to 20 slides with 20 seconds for each slide.

## Presentation

The online slides are [here](https://uea-teaching.github.io/pecha-kucha/slides/slides.html)

This presentation follows this script:

- My introduction and how I came to be here.
- What is computer science?
- What is computer vision?
- Working with faces.
- Presenting tips.

### Introduction

My presentation starts as a personal reflection, on how I arrived, by fairly unconventional means, to this field.

<!-- I wanted to use some ideas here, that I will use as I present to students. -->

I want to introduce at a very high level, what is computer science, and particularly computer vision.
I will then talk a little about working with faces.

Finally, I will make some remarks about presenting - including some items that have only recently become known to me.

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
