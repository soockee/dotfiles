# Use the Bash shell by default
SHELL := /bin/bash
.PHONY: all

all: help
help:
	@printf "There is no help ... you are doomed"

run: 
	ansible-playbook -i hosts site.yml --ask-become-pass

install: 
	ansible-galaxy install -r requirements.yml