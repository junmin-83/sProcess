1. sudo yum update
2. sudo yum upgrade
3. RPM으로 설치

wget https://kojipkgs.fedoraproject.org//vol/fedora_koji_archive01/packages/compat-gcc-34/3.4.6/34.fc21/x86_64/compat-libf2c-34-3.4.6-34.fc21.x86_64.rpm

wget https://kojipkgs.fedoraproject.org//vol/fedora_koji_archive01/packages/compat-gcc-34/3.4.6/34.fc21/x86_64/compat-gcc-34-3.4.6-34.fc21.x86_64.rpm

wget https://kojipkgs.fedoraproject.org//vol/fedora_koji_archive01/packages/compat-gcc-34/3.4.6/34.fc21/x86_64/compat-gcc-34-debuginfo-3.4.6-34.fc21.x86_64.rpm

--> 다운받은 파일을 yum install로 설치

4. sudo yum install gcc-gfortran

5. git clone https://github.com/rafael1193/suprem4gs.git

6. cd suprem4gs

7. vim Makefile
--> 'gcc'를 'gcc34'로
--> 'g77'을 'gfortran'으로

8. make depend install

9. mv bin suprem

10. ./suprem4gs

11. 소스코드로 이동하여
--> source boron.in 으로 시뮬레이션
