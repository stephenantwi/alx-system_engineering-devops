echo '#!/bin/bash' > 0-current_working_directory

	echo 'pwd' >> 0-current_working_directory

	chmod u+x 0-current_working_directory




1) 	echo '#!/bin/bash' > 1-listit

	echo 'ls' >> 1-listit

	chmod u+x 1-listit




2)	echo '#!/bin/bash' > 2-bring_me_home

	echo 'cd' >> 2-bring_me_home

	chmod u+x 2-bring_me_home



3)	echo '#!/bin/bash' > 3-listfiles

	echo 'ls -l' >> 3-listfiles 

	chmod u+x 3-listfiles



4)	echo '#!/bin/bash' > listmorefiles

	echo 'ls -la' >> 4-listmorefiles

	chmod u+x 4-listmorefiles



5)	echo '#!/bin/bash' > 5-listfilesdigitonly

	echo 'ls -lna' >> 5-listfilesdigitonly

	chmo u+x 5-listfilesdigitonly



6)	echo '#!/bin/bash' > 6-firstdirectory

	echo 'mkdir /tmp/my_first_directory' >> 6-firstdirectory

	chmod u+x 6-firstdirectory



7)	echo '#!/bin/bash' > 7-movethatfile

	echo 'mv /tmp/betty  /tmp/my_first_directory'  >> 7-movethatfile

	chmod u+x 7-movethatfile



8)	echo '#!/bin/bash' > 8-firstdelete

	echo 'rm /tmp/my_first_directory/betty' >> 8-firstdelete

	chmod u+x 8-firstdelete 



9)	echo '#!/bin/bash' > 9-firstdirdeletion

	echo 'rmdir /tmp/my_first_directory' >> 9-firstdirdeletion

	chmod u+x 9-firstdirdeletion



10)	echo '#!/bin/bash' > 10-back

	echo 'cd -' >> 10-back

	chmod u+x 10-back



11)	echo '#!/bin/bash' > 11-lists

	echo 'ls -la . .. /boot' >> 11-lists

	chmod u+x 11-lists



12)	echo '#!/bin/bash' > 12-file_type

	echo 'file /tmp/iamafile' >> 12-file_type

	chmod u+x 12-file_type



13)	echo '#!/bin/bash' > 13-symbolic_link

	echo 'ln -s  /bin/ls __ls__' >> 13-symbolic_link

	chmod u+x 13-symbolic_link



14)	echo '#!/bin/bash' > 14-copy_html

	echo 'cp -u *.html ../' >> 14-copy_html

	chmod u+x 14-copy_html



15)	echo '#!/bin/bash' > 100-lets_move

	echo 'mv [A-Z]* /tmp/u' >> 100-lets_move

	chmod u+x 100-lets_move



16)	echo '#!/bin/bash' > 101-clean_emacs
	
	echo 'rm *~' >> 101-clean_emacs
	
	chmod u+x 101-clean_emacs



17)	echo '#!/bin/bash' > 102-tree
	
	echo  'mkdir -p welcome/to/school' >> 102-tree
	
	chmod u+x 102-tree



18)	echo '#!/bin/bash' > 101-clean_emacs
		
	echo 'ls -apm | sort -d' >> 103-commas
	
	chmod u+x 101-clean_emacs



19)	echo '#!/bin/bash' > school.mgc
		
	echo '0 string SCHOOL School data' >> school.mgc 
	
	echo '!:mime school' >> school.mgc 
	
	chmod u+x school.mgc 
	
	file -C -m school.mgc *
	
	file --mime-type  -m school.mgc *
