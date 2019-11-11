# Semantic Git Versioning

## Resources
Explanation of what semantic versioning is can be found [here](https://semver.org/).
The repo that contains Git Versioning can be found [here](https://github.com/GitTools/GitVersion).

## How to use Git Versioning
### Linux
Inspired by [this](https://www.river.red/install-gitversion-ubuntu-16-04/).

1. Download the Git Version executable:
```wget https://github.com/GitTools/GitVersion/archive/5.1.2.tar.gz```

2. Extract executable
```tar -xf gitversion-linux-5.1.2.tar.gz```

3. Make symbolic link to execute exttracted file (<i>GitVersion</i>) from anywhere
```$ ln -S $(pwd)/GitVersion /usr/local/bin/gitversion```

Now you can call ```$ gitversion ``` from anywhere (should be in a git repo)




