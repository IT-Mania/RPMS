How to add on Fedora 32 (ps4linux)

cd /etc/yum.repos.d/

sudo wget https://raw.githubusercontent.com/IT-mania/RPMS/master/ps4.repo

sudo dnf update --refresh --repo ps4

If you have conflicts with LLVM-11:

sudo dnf install llvm-libs-10.0.0-1.fc32.i686

Done! Enjoy!
