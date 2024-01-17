The Odin Project's fundamental course
I added file and edited the file first without `git add README.md` first.
1. Add files `touch`
2. `git add filename.type` or `git add .` to add all files in current directory and all subsequent directories to the staging area.
3. `git commit -m "Add filename.type"`
4. `git push` or `git push origin master` to be more specific

Small tips I have learned –
1. `cd ..` is back to upper finder, `cd .` will take you back to the top
2. `rm filename.type` will remove the file
3. `git reset --hard` or `git reset --soft` will revert back to the certain point of status, `hard` is for local history, `soft` will move the HEAD, but leave the local files the same. source: https://stackoverflow.com/questions/3639115/reverting-to-a-specific-commit-based-on-commit-id-with-git