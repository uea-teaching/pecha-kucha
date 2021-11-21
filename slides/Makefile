HTM := $(patsubst %.md,%.html,$(wildcard *.md))

all : $(HTM)

%.html : %.md
	pandoc $^ \
	--defaults revealjs \
	--css assets/style.css \
	-V highlightjs-theme=atom-one-dark \
	-V theme=black \
	-V transition=slide \
	-V autoSlide=20000 \
	-o $@
