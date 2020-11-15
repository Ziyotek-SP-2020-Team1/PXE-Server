# pxe-server

1. Upload CentOS iso images into /tmp
2. Change variables in variables.txt
3. Run the script
4. Create password for root & other users and modify the lines in the .cfg file
5. Copy .cfg to the apporiate file path /var/ftp/"version of CentOS"
   example "centos7.cfg goes to /var/ftp/centos7/ "
6. Now your ready to setup an VM and install verison of CentOS via PXE Server
