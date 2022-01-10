# SAMP NODE EXAMPLE

This repository use:\
SAMP-NODE: https://github.com/AmyrAhmady/samp-node \
SAMP-NODE-LIB: https://github.com/peterszombati/samp-node-lib

You need to have installed:\
NODE: https://nodejs.org/ko/blog/release/v16.13.0 \
SAMPCTL: https://github.com/Southclaws/sampctl

## Installing packages

Execute this command to install samp packages on project root:
    `sampctl p ensure`

Install javascript packages:
    `npm i --prefix ./js` or `yarn --cwd ./js install`

## Running project

To run your project execute this command:
    `sampctl p run --forceBuild`
