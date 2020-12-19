# git-repo-generator
This is a script for making git repositories, LICENSE.txt, README.md, and remote repository URL.

### Usage
**install**
```bash
git clone https://github.com/TakutoYoshikai/git-repo-generator.git
echo /path/to/git-repo-generator/bin >> ~/.bash_profile
echo "your name" > /path/to/git-repo-generator/user.txt
cp license-without-copyright-line.txt /path/to/git-repo-generator/license-template.txt
```

**create a repository**
```bash
repo-gen <REPOSITORY NAME>
```

### License
MIT License
