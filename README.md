# alx-system_engineering-devops
devops learning

....alx-system_engineering-devops....
0x00-shell_basics,,,,
////////////////////////////////////////////
0-current_working_directory $pwd		
1-listit $ls
10-back $cd -
100-lets_move $mv [[:upper:]]* /tmp/u	
101-clean_emacs $rm *~
102-tree mkdir $-p welcome/to/school
103-commas $ls -map | sort -d
11-lists $ls -la . ..  /boot
12-file_type $file  /tmp/iamafile
13-symbolic_link $ln -s /bin/ls __ls__
14-copy_html $cp -R -u -p *.html ../
2-bring_me_home $cd /root
3-listfiles $ls -l
4-listmorefiles $ls -la
5-listfilesdigitonly $ls -la
6-firstdirectory $mkdir /tmp/my_first_directory
7-movethatfile $mv /tmp/betty /tmp/my_first_directory
8-firstdelete $rm /tmp/my_first_directory/betty
9-firstdirdeletion $rmdir /tmp/my_first_directory	
school.mgc

0x01-shell_permissions
///////////////////////////////////////////////////
0-iam_betty $su betty 
1-who_am_i $whoami
10-mirror_permissions $chmod --reference=olleh hello
100-change_owner_and_group $chown -hR vincent:staff .
101-symbolic_link_permissions $chown --from=guillaume betty hello
102-if_only $chown --from=guillaume betty hello
103-Star_Wars $telnet towel.blinkenlights.nl
11-directories_permissions $chmod a+X *
12-directory_permissions $mkdir -m 751 my_dir
13-change_group $chgrp school hello
2-groups $whoami
3-new_owner $chown betty hello
4-empty $touch hello
5-execute $chmod 744 hello
6-multiple_permissions $chmod 754 hello
7-everybody $chmod ugo+x hello
8-James_Bond $chmod 007 hello
9-John_Doe $chmod 753 hello
