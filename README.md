bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -d 10 -v 64 -p ciphercode -a -firmware

-u 14.04
-u 16.04

bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/dun11/vps_reinstall_debian/main/InstallNET.sh') -d 9 -v 32 -p ciphercode -a -firmware


#Debian 9
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/dun11/vps_reinstall_debian/main/InstallNET.sh') -d 9 -v 64 -a -firmware


#Debian 10
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/dun11/vps_reinstall_debian/main/InstallNET.sh') -d 10.3 -v 64 -a -firmware





bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh') -d 10 -v 64 -p ciphercode -a -firmware


​    bash InstallNET.sh   -d/--debian [dist-name]

​                -u/--ubuntu [dist-name]

​                -c/--centos [dist-version]

​                -v/--ver [32/i386|64/amd64]

​                -p

​                --ip-addr/--ip-gate/--ip-mask

​                -apt/-yum/--mirror

​                -dd/--image

​                -a/-m




master:
https://moeclub.org/attachment/LinuxShell/InstallNET.sh



wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd 'https://oss.sunpma.com/Windows/Win_Server2008R2_sp1_64_Administrator_nat.ee.gz'

