# ansible-include-vars-dir

Includes all YAML files under given path(s).

[![Build Status](https://travis-ci.org/osxstrap/ansible-include-vars-dir.svg?branch=master)](https://travis-ci.org/osxstrap/ansible-include-vars-dir)

## Requirements

## Role Variables

Available variables are listed below, along with default values:

    # List of local paths to search for YAML files
    # that will be included as Ansible vars.
    include_vars_dir_paths: []

    # Extension of files to include.
    include_vars_file_extension: "yml"

    # Exclude files matching this name
    #include_vars_dir_exclude_name: "requirements.yml"

    # Directory depth to used search for files
    # 1 = only files directly in include_vars_dir_paths
    include_vars_dir_depth: 1

## Dependencies

## Example Playbook

    - hosts: all
      roles:
        - { role: jeremyltn.include-vars-dir }

## License

MIT
