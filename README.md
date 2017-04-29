#### Description

Just a proof of concept.
Creates a deb package with executable my-package which is a script that calls uberjar compiled by this project.

#### Basic usage


```
mvn clean package
sudo dpkg -i target/my-package_1.0.0-1_all.deb
sudo dpkg --contents target/my-package_1.0.0-1_all.deb
my-package-run
sudo dpkg --remove my-package
```

#### Links
http://debian-maven.sourceforge.net/usage.html
