# Personal Website

## How to modify source code

1. Make changes in the source code in [calvincodes.github.io-src](https://github.com/calvincodes/calvincodes.github.io-src) repo.
2. Run it locally using `hugo server`
3. Push changed to origin in [calvincodes.github.io-src](https://github.com/calvincodes/calvincodes.github.io-src)

## How to deploy modified source code

1. Make a fresh clone of [calvincodes.github.io](https://github.com/calvincodes/calvincodes.github.io) on your local.
2. Copy the modified files from source repo to this fresh clone.
3. Remove the public folder from this cloned repo (rm -rf public)
4. `git submodule add -f -b master https://github.com/calvincodes/calvincodes.github.io.git public`
5. Commit the modified files and public folder - then push them to origin.
6. Now regenrate the public folder and push it to origin again

`hugo`

`cd public`

`git add .`

`git commit -m "Build website"`

`git push origin master`

`cd ..`
