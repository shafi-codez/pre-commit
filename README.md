# pre-commit
Use Precommit hooks

Install pre commit

```pip install pre-commit```
or

```brew install pre-commit```


Add
```
vi .git/hooks/pre-commit
pip install pre-commit-hooks
pre-commit run --all-files
chmod +x .git/hooks/pre-commit

git commit -m "Text"
````
