> #### yum configuration
>
> - go to ```http://mirrors.163.com/centos/7/os/x86_64/Packages/ ```
>> - download python-pycurl-7.19.0-19.el7.x86_64.rpm
>> - python-urlgrabber-3.10-10.el7.noarch.rpm
>> - yum-metadata-parser-1.1.4-10.el7.x86_64.rpm
> - ```rpm -ivh *.rpm```
> - ``` wget http://yum.baseurl.org/download/3.4/yum-3.4.3.tar.gz```
> - ```tar -xvf  yum-3.4.3.tar.gz ```
> - ``` touch /etc/yum.conf```
> - ```cd yum-3.4.3/;./yummain.py install yum```
