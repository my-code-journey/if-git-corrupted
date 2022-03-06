# if-git-corrupted
For my own reference, what to do if github repo is corrupt


    find .git/objects/ -type f -empty | xargs rm
    git fetch -p
    git fsck --full
    
  
 for more solutions go to https://stackoverflow.com/questions/11706215/how-can-i-fix-the-git-error-object-file-is-empty 
    
