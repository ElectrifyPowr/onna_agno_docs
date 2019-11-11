# Semantic Git Versioning

## Resources
Explanation of what semantic versioning is can be found [here](https://semver.org/).<br>
The repo that contains Git Versioning can be found [here](https://github.com/GitTools/GitVersion).

## How to install Git Versioning
### Linux
Inspired by [this](https://www.river.red/install-gitversion-ubuntu-16-04/).

1. Download the Git Version executable (from command line or simply copy the link into browser):<br>
- Linux: ```$ wget https://github.com/GitTools/GitVersion/releases/download/5.1.2/gitversion-linux-5.1.2.tar.gz```
- Windows: ```$ wget https://github.com/GitTools/GitVersion/releases/download/5.1.2/gitversion-windows-5.1.2.tar.gz```
- Mac: ```$ wget https://github.com/GitTools/GitVersion/releases/download/5.1.2/gitversion-osx-5.1.2.tar.gz```

2. Extract executable (replace <i>'YOUR_OS'</i> with either <i>linux</i>,<i>windows</i>,<i>osx</i>):<br>
```$ tar -xf gitversion-YOUR_OS-5.1.2.tar.gz```

3. Executing it
- Linux & Mac: Make symbolic link to execute exttracted file (<i>GitVersion</i>) from anywhere with<br>
```$ ln -S $(pwd)/GitVersion /usr/local/bin/gitversion```
- Windows: Simply copy the file to the git repo

## Usage

If you are not sure how to use the downloaded git-versioning-tool, enter following command:
- Linux & Mac: ```$ GitVersion ?```
- Windows: ```$ GitVersion.exe ?```

By entering ```$ GitVersion``` you will get a JSON file printed to the standard output.


