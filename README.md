# ansible-include-vars-dir

Includes all YAML files under given path(s).

[![Build Status](https://travis-ci.org/osxstrap/ansible-include-vars-dir.svg?branch=master)](https://travis-ci.org/osxstrap/ansible-include-vars-dir)

## Requirements

## Role Variables

Available variables are listed below, along with default values:

	# List of local paths (separated by spaces) to search
	# for YAML files that will be included as Ansible vars.
	include_vars_dir_paths: ""

## Dependencies

## Example Playbook

    - hosts: all
      roles:
        - { role: jeremyltn.include-vars-dir }

## License

MIT
