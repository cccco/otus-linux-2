Exercise1.1

После отработки vagrant up  и vagrant ssh выполняем внутри виртуальной машины следующие комманды:

sudo -i

cd /usr/src/linux-5.2.5/

make -j8

make modules_install

make install

grub2-set-default 0

reboot

Результат 

![Результат сборки и установки ядра](https://github.com/perhamm/otus-linux/blob/master/Ex01/ex1.PNG)



Доустановленные пакеты 

Jul 31 17:44:56 Installed: mpfr-3.1.1-4.el7.x86_64
Jul 31 17:44:56 Installed: libmpc-1.0.1-3.el7.x86_64
Jul 31 17:44:56 Installed: m4-1.4.16-10.el7.x86_64
Jul 31 17:44:57 Installed: zlib-devel-1.2.7-18.el7.x86_64
Jul 31 17:44:57 Installed: cpp-4.8.5-36.el7_6.2.x86_64
Jul 31 17:44:57 Installed: 1:perl-parent-0.225-244.el7.noarch
Jul 31 17:44:58 Installed: perl-HTTP-Tiny-0.033-3.el7.noarch
Jul 31 17:44:58 Installed: perl-podlators-2.5.1-3.el7.noarch
Jul 31 17:44:58 Installed: perl-Pod-Perldoc-3.20-4.el7.noarch
Jul 31 17:44:58 Installed: 1:perl-Pod-Escapes-1.04-294.el7_6.noarch
Jul 31 17:44:58 Installed: perl-Text-ParseWords-3.29-4.el7.noarch
Jul 31 17:44:58 Installed: perl-Encode-2.51-7.el7.x86_64
Jul 31 17:44:58 Installed: perl-Pod-Usage-1.63-3.el7.noarch
Jul 31 17:44:58 Installed: 4:perl-libs-5.16.3-294.el7_6.x86_64
Jul 31 17:44:58 Installed: 4:perl-macros-5.16.3-294.el7_6.x86_64
Jul 31 17:44:58 Installed: 4:perl-Time-HiRes-1.9725-3.el7.x86_64
Jul 31 17:44:58 Installed: perl-Exporter-5.68-3.el7.noarch
Jul 31 17:44:58 Installed: perl-constant-1.27-2.el7.noarch
Jul 31 17:44:58 Installed: perl-Time-Local-1.2300-2.el7.noarch
Jul 31 17:44:58 Installed: perl-Carp-1.26-244.el7.noarch
Jul 31 17:44:58 Installed: perl-Storable-2.45-3.el7.x86_64
Jul 31 17:44:58 Installed: perl-PathTools-3.40-5.el7.x86_64
Jul 31 17:44:58 Installed: perl-Scalar-List-Utils-1.27-248.el7.x86_64
Jul 31 17:44:58 Installed: perl-File-Temp-0.23.01-3.el7.noarch
Jul 31 17:44:58 Installed: perl-File-Path-2.09-2.el7.noarch
Jul 31 17:44:58 Installed: perl-threads-shared-1.43-6.el7.x86_64
Jul 31 17:44:58 Installed: perl-threads-1.87-4.el7.x86_64
Jul 31 17:44:58 Installed: perl-Filter-1.49-3.el7.x86_64
Jul 31 17:44:58 Installed: perl-Socket-2.010-4.el7.x86_64
Jul 31 17:44:58 Installed: 1:perl-Pod-Simple-3.28-4.el7.noarch
Jul 31 17:44:58 Installed: perl-Getopt-Long-2.40-3.el7.noarch
Jul 31 17:45:00 Installed: 4:perl-5.16.3-294.el7_6.x86_64
Jul 31 17:45:00 Installed: libkadm5-1.15.1-37.el7_6.x86_64
Jul 31 17:45:00 Installed: pcre-devel-8.32-17.el7.x86_64
Jul 31 17:45:00 Installed: libsepol-devel-2.5-10.el7.x86_64
Jul 31 17:45:00 Installed: libselinux-devel-2.5-14.1.el7.x86_64
Jul 31 17:45:00 Installed: libverto-devel-0.2.5-4.el7.x86_64
Jul 31 17:45:00 Installed: libcom_err-devel-1.42.9-13.el7.x86_64
Jul 31 17:45:01 Installed: kernel-headers-3.10.0-957.27.2.el7.x86_64
Jul 31 17:45:01 Installed: glibc-headers-2.17-260.el7_6.6.x86_64
Jul 31 17:45:01 Installed: glibc-devel-2.17-260.el7_6.6.x86_64
Jul 31 17:45:01 Installed: keyutils-libs-devel-1.5.8-3.el7.x86_64
Jul 31 17:45:02 Installed: krb5-devel-1.15.1-37.el7_6.x86_64
Jul 31 17:45:02 Installed: 1:openssl-devel-1.0.2k-16.el7_6.1.x86_64
Jul 31 17:45:04 Installed: gcc-4.8.5-36.el7_6.2.x86_64
Jul 31 17:45:04 Installed: elfutils-libelf-devel-0.172-2.el7.x86_64
Jul 31 17:45:04 Installed: flex-2.5.37-6.el7.x86_64
Jul 31 17:45:04 Installed: bison-3.0.4-2.el7.x86_64
Jul 31 17:45:04 Installed: bc-1.06.95-13.el7.x86_64
Jul 31 17:45:04 Installed: ncurses-devel-5.9-14.20130511.el7_4.x86_64



