<div align="center">

# Forks

Keep all your forks up to date with the remote master branch.

[![Build Status](https://travis-ci.com/Justintime50/forks.svg?branch=master)](https://travis-ci.com/Justintime50/forks)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

<img src="assets/showcase.png">

</div>

If you manage more than a couple forks, keeping them up to date with the remote master can be a pain. Sure you can merge them in on GitHub but that creates a merge commit which nobody wants, then if you choose to merge any of your changes into the remote repo, they get your lovely merge commits when all you wanted was to stay up to date. Forks lets you avoid all that.

## Install

```bash
pip3 install -r requirements.txt
```

## Usage

It's recommended to use Forks away from your development repos so as to not get merge conflicts. Forks will clone your projects locally, add the remote upstream, fetch upstream changes, pull them in, and force push them to your origin repo. Cloning or updating forks will timeout after 120 seconds per fork.

```bash
python3 forks.py
```