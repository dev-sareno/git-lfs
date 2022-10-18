# git-lfs
Demo project for Git LFS

## Install Git LFS on your machine
Visit [https://git-lfs.github.com/](https://git-lfs.github.com/)

## Install LFS extention
```sh
$ git lfs install
```
or add `--skip-smudge` flag to exclude LFS files on clone
```sh
$ git lfs install --skip-smudge
```

## Tracking
```sh
$ git lfs track "*.psd" "*.jpeg" "*.jpg" "*.png"
$ git add .gitattributes
```

## Cloning
```sh
$ git clone git@github.com:dev-sareno/git-lfs.git
```
or explicitly exclude LFS files (if `--skip-smudge` is not set)
```sh
$ GIT_LFS_SKIP_SMUDGE=1 git clone git@github.com:dev-sareno/git-lfs.git
```
