
# Data description
The original lock files are included in the `original` folder,
the lock files produced by `npm dedupe` are included in the `npm_dedupe` folder,
and the lock files produced by DeepDeDupe are included in the `deepdedupe` folder.
To indicate which project the lock file belong to, a prefix of the repo name is added to `package-lock.json`.

# Data usage
Check the lock files to see the effect of duplication reduction.
Use `npm install` to see impact on storage and time. 


