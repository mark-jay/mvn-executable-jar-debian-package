# http://debian-maven.sourceforge.net/usage.html

mvn clean package
sudo dpkg -i target/my-package_1.0.0-1_all.deb
sudo dpkg --contents target/my-package_1.0.0-1_all.deb
sudo dpkg --remove my-package
