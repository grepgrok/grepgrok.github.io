# grepgrok.github.io

FYI, you can selectively merge files: (here merging `myfile.txt` from `source` to `destination`)

```bash
git checkout destination
git checkout dev -- myfile.txt
# Or skip the `--`
# Resolve conflicts
git commit -am "merge: [message]"
git push
```

