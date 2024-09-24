### Setup

```sh
cd project1 && python3 -m venv --prompt "project1" .venv
cd project2 && python3 -m venv --prompt "project2" .venv
```

### Bug

Now check the `global.py` file.
It should NOT be in any venv, but it is. You can verify this at the bottom right or via "Create New Terminal" or "Create New Terminal (In Active Workspace)".
