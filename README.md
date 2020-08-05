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
    
