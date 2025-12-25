<h1>Complete Git Command </h1>

**Video:** _Master Git Like a Pro by Tapas Adhikari._

**Link:** [tapaScript](https://www.youtube.com/watch?v=bcpz73hbt8c)

## Log

```
git log
git log --oneline
git reflog

```

## Reset

```
git reset --hard <commit_id>
example: git reset --hard 61ca65de100c19cfcd0b8f0b31647431d75e12be

```

## Remove

From staging area: A file is upload to staged/ commited. Now want to `Untracked` again:

```
git rm --cached <fileName>
```

## Changing branch

```
git switch <branchName>

<!-- best way -->
git checkout <branchName>
```
