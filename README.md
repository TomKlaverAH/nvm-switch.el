# nvm-switch.el
Switch nvm node versions in emacs

This adds the interactive command `nvm-switch-select-node-version`
that selects a NodeJS version from `nvm` and update `exec-path' and `PATH` in
`process-environment`.

This should cause any spawned processes to use the select NodeJS version.

The `.nvm` directory can be customized in `nvm-switch-directory`.
