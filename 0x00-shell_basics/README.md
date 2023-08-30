###[0-current_working_directory](0-current_working_directory)
pwd

###[1-listit](1-listit)
ls

###[2-bring_me_home](2-bring_me_home)
cd home

###[3-listfiles](3-listfiles)
ls -l

###[4-listmorefiles](4-listmorefiles)
ls -la

###[5-listfilesdigitonly](5-listfilesdigitonly)
ls -lna

###[6-firstdirectory](6-firstdirectory)
mkdir /tmp/my_first_directory

###[7-movethatfile](7-movethatfile)
mv /tmp/betty /tmp/my_first_directory

###[8-firstdelete](8-firstdelete)
rm /tmp/my_first_directory/betty

###[9-firstdirdeletion](9-firstdirdeletion)
rmdir /tmp/my_first_directory

###[10-back](10-back)
cd -

###[11-lists](11-lists)
ls -la . .. /boot

###[12-file_type](12-file_type)
file /tmp/iamafile

###[13-symbolic_link](13-symbolic_link)
ln -s /bin/ls __ls__

###[14-copy_html](14-copy_html)
cp -u *.html ..
