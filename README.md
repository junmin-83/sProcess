1. sudo yum update
2. sudo yum upgrade
3. git clone https://github.com/junmin-83/sProcess.git
4. RPM 설치 
cd sProcess
cd RPM
yum install ./*.rpm

[참고]
wget https://kojipkgs.fedoraproject.org//vol/fedora_koji_archive01/packages/compat-gcc-34/3.4.6/34.fc21/x86_64/compat-libf2c-34-3.4.6-34.fc21.x86_64.rpm
wget https://kojipkgs.fedoraproject.org//vol/fedora_koji_archive01/packages/compat-gcc-34/3.4.6/34.fc21/x86_64/compat-gcc-34-3.4.6-34.fc21.x86_64.rpm
wget https://kojipkgs.fedoraproject.org//vol/fedora_koji_archive01/packages/compat-gcc-34/3.4.6/34.fc21/x86_64/compat-gcc-34-debuginfo-3.4.6-34.fc21.x86_64.rpm

5. sudo yum install gcc-gfortran

6. vim Makefile
--> 'gcc'를 'gcc34'로
--> 'g77'을 'gfortran'으로

7. make depend install

8. mv bin suprem

9. chmod +x ./suprem4gs

11. ./suprem4gs

10. 소스코드로 이동하여
--> source boron.in 으로 시뮬레이션
