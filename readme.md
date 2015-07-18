# Deployment Plan push from local to staging 
1. ```git add -A```
2. ```git commit -q -m “descriptive comment”```
3. ```git push stageServer```
4. ```git tag -a vX.X.X -m “note version number”```
5. ```git push stageServer --tags```


# Deployment Plan push from local to production 

1. ```git push prodServer```
2. ```git tag -a vX.X.X -m ‘note version number’```
3. ```git push prodServer —tags```