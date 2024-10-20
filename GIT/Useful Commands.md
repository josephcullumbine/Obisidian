**Config:**

Change Config file:

```
git config --global --edit
```

Set VS Code as default editor:

```
git config --global core.editor "code --wait"
```

Set key config settings:

```
git config --global user.name "Alfredo Linguini"
git config --global user.email "a.linguini@ratatouille.fr"
```

**Key Commands:**

Create a Repository

```
git init
```

Check status

```
git status
```

Add files to staging area

```
git add filename.ext  (Use -a to add all)
```

Commit files

```
git commit -m "message"
```

List all commits

```
git log (-N where `N` is the number of commits that you want to view)
```

View differences between versions/before committing

```
git diff (Use --staged to compare to staged file) (HEAD~N to compare to previous commits)
```

View previous commits

```
git show HEAD~2 filename.ext
```

Restore previous commits

```
git restore (-s HEAD~N) filename.ext
```

Let git ignore files we don't want to track

Add to .gitignore

```
*.png (All files with this extension)
!final.png (The exclamation point operator will include a previously excluded entry.)
receipts/ (All files in this directory)
```

View status of ignored files

```
git status --ignored
```

**Remote Repository:**

- Create Repository on GitHub or equivalent
- Add remote repository

```
git remote add origin git@github.com:name/repo_name.git
```

- Check it worked

```
git remote -v
```

```
git push origin main
```
