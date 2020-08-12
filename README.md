# Java
It's the repository for Java study

### In Linux, How to compress the Folder or file

1. Compress Folder
    - $ tar -cvf filename.tar Folder
    - $ tar -zcvf filename.tar.gz Folder
    - $ zip filename.zip -r ./* (Compress current directories and subdirectories)
    - $ zip filename.zip ./* (Compress current directories)

2. Uncompress file
    - $ tar -xvf filename.tar
    - $ tar -zxvf filename.tar.gz
    - $ unzip filename.zip
    - $ unzip filename.zip -d ./target (If you want to uncompress file on the specific directories)
    
3. Option for umcompressing
    - "-c": compress tar
    - "-p": file permission
    - "-v": show the process
    - "-f": name the file
    - "-C": directory
    - "-x": uncompress tar
    - "-z": compress or uncompress gzip file
    
### In Linux, How to update JAVA

First, check the version of JAVA
$ java -version

Second, check the version I can install
$ yum list java*jdk-devel

Third, install
$ yum install -y java-11-openjdk-devel.x86_64

Forth, check again the version of JAVA
$ java -version

If it was updated, skip the next step

If it was not updated, typing $ sudo /usr/sbin/alternatives --config java and then check again the version
