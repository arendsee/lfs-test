This is a test of the Large File System, this is only a test

If you have not already installed LFS, install it on your system

Download the binary from https://github.com/github/git-lfs and run the install
script, which removes all existing versions and installs the new one.

```
git init
git remote add origin git@github.com:arendsee/lfs-test.git
git lfs track "\*.dat"
echo "hello" > big.dat
git add -A
git commit -m 'Test'
git push origin master
```
