SLIDES_DIR := .
OUTPUT     := $(SLIDES_DIR)/main.pdf
COMPOSE    := docker compose

.PHONY: all build image clean distclean pull open

all: build

image:
	$(COMPOSE) build

build: image
	$(COMPOSE) run --rm latex

clean:
	@echo "Removing auxiliary files…"
	@rm -f $(SLIDES_DIR)/main.aux \
	        $(SLIDES_DIR)/main.bbl \
	        $(SLIDES_DIR)/main.bcf \
	        $(SLIDES_DIR)/main.blg \
	        $(SLIDES_DIR)/main.fdb_latexmk \
	        $(SLIDES_DIR)/main.fls \
	        $(SLIDES_DIR)/main.log \
	        $(SLIDES_DIR)/main.nav \
	        $(SLIDES_DIR)/main.out \
	        $(SLIDES_DIR)/main.run.xml \
	        $(SLIDES_DIR)/main.snm \
	        $(SLIDES_DIR)/main.toc \
	        $(SLIDES_DIR)/main.vrb

distclean: clean
	@echo "Removing output PDF…"
	@rm -f $(OUTPUT)

pull:
	docker pull texlive/texlive:latest-small
	$(COMPOSE) build --no-cache

open: $(OUTPUT)
	open $(OUTPUT)
