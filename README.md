# Git Swap

This project has come out of my annoying habit of committing to my personal repos with my work account and more embarrassingly committing to my work repos with my personal account.

Idea came from <a href="https://github.com/joealba/gitswitch">https://github.com/joealba/gitswitch</a>, a ruby git profile switcher.

## Install

    npm install -g gitswap

## Usage

To initialize, run:

    gitswap

Gitswap will read your `.gitconfig` file and check for a `.gitswap` file in your home directory, if one is not present, it will ask you to create one.

It takes the current username and email in your `.gitconfig` file and places these under the tag of orig.

Run `gitswap` again and it will ask you to add further tags, add as many as required.

To swap between profiles:

    gitswap [tag];


@TODO
* sort out the file crud, duplicate logic
* organise the flow
* error handling