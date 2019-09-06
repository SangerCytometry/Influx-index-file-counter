This page has been archived and further updates will be on Christopher’s [GitHub page]( https://github.com/hally166/Influx-index-file-counter).

# Index file counter

Copyright (c) 2017 Genome Research Ltd.

Author : Christopher Hall, Wellcome Trust Sanger Institute.

http://www.sanger.ac.uk/science/groups/cytometry-core-facility

When asked by management for statistics on index sorting by our customers we wrote this script.  It will trawl though the folders and count the number of index .fcs files and the number of folders that contain them. We use a folder structure that allows us to count index experiments and users.  It is: C:\INFLUX files\User 1\01Jan17\somefile.fcs

Remember this script takes advantage of our data storage structure at the Sanger Institute.  If you organise your user files differently it will not work.  However you are free to adjust the script to allow it to wiork in your system.

## INSTRUCTIONS
Place the script into the top directory of your users .fcs file storage area.

Run the script, it will take a while, but it will also display the filename and path of every index file it finds to let you know it is running.

It will produce a stats.csv file with all the statisitcs you need and place it in the same folder as the python script.
