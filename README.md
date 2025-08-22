# mmWave TI ROS package
This repo is a mirror of the [Texas Instruments mmwave ros library](https://git.ti.com/cgit/mmwave_radar/mmwave_ti_ros/)

#### Syncing with the Original Repository
This repository is a mirror of the original mmwave_ti_ros project from the TI Git server. To keep your fork up-to-date with any new changes from the original source, you'll need to periodically pull updates.

Add the original repository as a remote (you only need to do this once).

```Bash
git remote add upstream https://git.ti.com/git/mmwave_radar/mmwave_ti_ros.git
```
Fetch the latest changes from the original remote.
```Bash
git fetch upstream
```
Merge the changes into your master branch.
```Bash
git checkout master
git merge upstream/master
```
Push the updates to your GitHub repository.
```Bash
git push origin master
```
This process ensures your fork stays in sync, so you'll always have the latest code.
