# Python book

[intro TKTKTK]

Reminder to nix: run the auto-gen with the following code

```bash
watchmedo shell-command \
    --command='echo "${watch_src_path}"; jupyter-book build .' \
    --patterns="*.ipynb;*.yml;*.md" \
    --ignore-patterns="**/_build/**;**/.ipynb_checkpoints/**" \
    --recursive --wait --drop
```
