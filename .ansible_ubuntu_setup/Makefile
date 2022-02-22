# Use the Bash shell by default
SHELL := /bin/bash
.PHONY: all

all: help
help:
	@printf "There is no help ... you are doomed"

install: 
	ansible-playbook -i hosts site.yml --ask-become-pass
