# cli
--create a hidden file or folder:
$ touch hi.txt && attrib +h hi.txt


--create a hidden folder:
$ mkdir hi && attrib +h hi


--show hidden file :
$ attrib -h hi.txt


--show hidden file or folder:
$ attrib -h hi


create multiple nested directories
$ mkdir -p c/Users/Administrator/these/files/are/just/for/fun


append a message to a file, without a newline character :
$ echo "first message
second message" >> hi.txt

