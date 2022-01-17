# nvm-switch.el
Switch nvm NodeJS versions in Emacs

This adds the interactive command `nvm-switch-select-node-version`
that selects a NodeJS version from `nvm` and updates `'exec-path` and `PATH` in
`'process-environment`.

This should cause any spawned processes to use the selected NodeJS version.

The `.nvm` directory can be customized in `nvm-switch-directory`.
