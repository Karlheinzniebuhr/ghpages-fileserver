# Github Pages Fileserver
A simple fileserver which runs on top of Github pages

## DEMO
[http://karlheinzniebuhr.github.io/resources.html](http://karlheinzniebuhr.github.io/resources/)

## Get started
- Setup your Github page here https://pages.github.com/ 
- Clone it:
```bash
git clone https://github.com/username/username.github.io
```
- Clone ghpages-fileserver
```bash
git clone https://github.com/Karlheinzniebuhr/ghpages-fileserver
```
- Move or copy content to username.github.io folder  
```bash
cp -r ghpages-fileserver/ username.github.io/
```
- Start Jekyll
```bash
cd username.github.io
jekyll serve
```
- Open Webbrowser at [http://localhost:4000/](http://localhost:4000/)

## Add content to your server
- Just put your stuff inside the /resources/ folder and commit & push
- Open your page at https://username.github.io

## Important
Github will complain if you host binaries and/or very large files. If you upload Binaries compress (Zip) them first and try to not abuse with file size. 
