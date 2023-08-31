###[0-iam_betty](0-iam_betty)
su betty

###[1-who_am_i](1-who_am_i)
whoami

###[2-groups](2-groups)
groups

###[3-new_owner](3-new_owner)
sudo chown betty hello

###[4-empty](4-empty)
touch hello

###[5-execute](5-execute)
chmod u+x hello

###[6-multiple_permissions](6-multiple_permissions)
chmod ug+x,o+r hello

###[7-everybody](7-everybody)
chmod a+x hello

###[8-James_Bond](8-James_Bond)
chmod 007 hell0

###[9-John_Doe](9-John_Doe)
chmod 753 hello

###[10-mirror_permissions]
chmod --reference=olleh hello

###[11-directories_permissions](11-directories_permissions)
chmod -R a+X .

###[12-directory_permissions](12-directory_permissions)
mkdir -m 751 my_dir

###[13-change_group](13-change_group)
chgrp school hello
