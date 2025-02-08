# Git
* add
    ```bash
    git add
            ./                    # add all
            filename.tsx          # add file
            ./somefolder/file.md  # add path to folder
            -A                    # add all
    ```
* commit
```bash
git commit -m "required message(identificator)"
           --amend # хочу перезатереть предыдущий комит, при использовании amend, push команда -f
           --no-edit # не изменять параметр -m
```