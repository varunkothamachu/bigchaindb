# How to Install OS-Level Dependencies

BigchainDB Server has some OS-level dependencies that must be installed.

On Ubuntu 14.04, we found that the following was enough:
```text
sudo apt-get update
sudo apt-get install g++ python3-dev
```

On Fedora 23, we found that the following was enough (tested in February 2015):
```text
sudo dnf update
sudo dnf install gcc-c++ redhat-rpm-config python3-devel
```

(If you're using a version of Fedora before version 22, you may have to use `yum` instead of `dnf`.)