# jekyll-bootstrap 4 -Gulp
Starter project using Jekyll for creating websites with Bootstrap 4.
And cool use of gulp stuff : file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.

## Usage
1. Download and extract the [ZIP archive](https://github.com/astrocycles/S-E/archive/master.zip)
2. Rename the extracted folder and remove the README file

### System Prerequisite
 - [Ruby](https://www.ruby-lang.org/en/downloads/) - use the installer
 - [Jekyll](https://jekyllrb.com/) - ```$ gem install jekyll```
 - [NodeJS](https://nodejs.org/en/download/) - use the installer.

### development

 ```shell

$ git clone
$ cd folder-name
$ npm install
$ gulp
# the browser should open and refresh each time you save
```
### prod

```shell

# be sure you start from a fresh GitHub state
$ rm -rf .git
$ git init
$ git add . && git commit -m 'initial commit'
$ git remote add origin git@github.com:<your_github_name>/<your_repo_name>.git
# in config.prod.yml, set baseurl to <your_repo_name>
$ git push -u origin master
$ gulp deploy
# go see your site :
# https://<your_github_name>/<your_repo_name>/
```
## credit

- [Shane Osbourne, jekyll-gulp-sass-browser-sync](https://github.com/shakyShane/jekyll-gulp-sass-browser-sync)
- [David Boureau, aka:
bdavidxyz]https://github.com/bdavidxyz/impatient-
- [jenofdoom]https://github.com/jenofdoom/jekyll-bootstrap-4
- [travis Neilson- in the design code serie (depreciated)]: https://github.com/travisneilson
