
Set this in your .zshrc file, preferably at the beginning:
```zsh
export FYW_DIR="<path_to_fyw_dir>" # a good example: ~/.config/fyw
export FYPM_DIR="<path_to_fypm_repo>"
export FYSM_DIR="<path_to_fysm_repo>"

source $FYW_DIR/config/fywrc
```

After all, copy "config" file from this rep to your $FYW_DIR and change the values in those scripts.
