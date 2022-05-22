# api-docs
This is the Tiui API documentation


In here: /Users/../api-master  --- (this is one folder before where the documentation is) 

Run command to generate the new html file: 
npx redoc-cli build demo/openapi.yaml

Change name of generated File: 
mv redoc-static.html index.html

To move it directly to Github
git checkout -b new_branch

git add .

git commit “new commit”

git push -u origin new_branch

Do pull request online y esperar
