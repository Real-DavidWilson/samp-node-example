# samp node project example

This repository use:\
samp-node: https://github.com/AmyrAhmady/samp-node \
samp-node-lib: https://github.com/peterszombati/samp-node-lib

You need to have installed:\
node: https://nodejs.org/ko/blog/release/v16.13.0 \
sampctl: https://github.com/Southclaws/sampctl

## Installing packages

Execute this command to install samp packages on project root:
    `sampctl p ensure`

Install javascript packages:
    `npm i --prefix ./js` or `yarn --cwd ./js install`

## Running project

To run your project execute this command:
    `sampctl p run --forceBuild`
