# GCC_On_Ubuntu20
Install GCC_9.3.0 on Ubuntu_20.04(LTS) without Internet

1. Install make from liveCD
2. Download all the nessasary deb files from internet and copy them to a flash disk
3. Insert the flash disk to Ubuntu_20.04 machine, locate the folder contains deb files in terminal and then type the following commands:
    sudo apt-get install ./manpages-dev_5.05-1_all.deb
    sudo apt-get install ./libcrypt-dev_4.4.10-10ubuntu4_amd64.deb
    sudo apt-get install ./linux-libc-dev_5.4.0-42.46_amd64.deb
    sudo apt-get install ./libc-dev-bin_2.31-0ubuntu9_amd64.deb
    sudo apt-get install ./libc6-dev_2.31-0ubuntu9_amd64.deb
    sudo apt-get install ./binutils-common_2.34-6ubuntu1_amd64.deb
    sudo apt-get install ./libbinutils_2.34-6ubuntu1_amd64.deb
    sudo apt-get install ./libctf0_2.34-6ubuntu1_amd64.deb
    sudo apt-get install ./libctf-nobfd0_2.34-6ubuntu1_amd64.deb
    sudo apt-get install ./binutils-x86-64-linux-gnu_2.34-6ubuntu1_amd64.deb
    sudo apt-get install ./binutils_2.34-6ubuntu1_amd64.deb
    sudo apt-get install ./libitm1_10-20200411-0ubuntu1_amd64.deb
    sudo apt-get install ./libatomic1_10-20200411-0ubuntu1_amd64.deb
    sudo apt-get install ./libasan5_9.3.0-10ubuntu2_amd64.deb
    sudo apt-get install ./liblsan0_10-20200411-0ubuntu1_amd64.deb
    sudo apt-get install ./libtsan0_10-20200411-0ubuntu1_amd64.deb
    sudo apt-get install ./libubsan1_10-20200411-0ubuntu1_amd64.deb
    sudo apt-get install ./libquadmath0_10-20200411-0ubuntu1_amd64.deb
    sudo apt-get install ./libgcc-9-dev_9.3.0-10ubuntu2_amd64.deb
    sudo apt-get install ./gcc-9_9.3.0-10ubuntu2_amd64.deb
    sudo apt-get install ./gcc_9.3.0-1ubuntu2_amd64.deb
4. Check gcc version through gcc -v
