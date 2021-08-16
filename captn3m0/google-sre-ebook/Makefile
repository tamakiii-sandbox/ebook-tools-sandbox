.PHONY: help build clean

help:
	@cat $(firstword $(MAKEFILE_LIST))

build:
	docker run --rm --volume $(realpath .):/output -e BOOK_SLUG='srw_book' captn3m0/google-sre-ebook:latest

clean:
	rm google-the-site-reliability-workbook.*
