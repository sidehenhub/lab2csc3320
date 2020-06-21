# Summary of what I did for this assignment
1. first use the "cd" cmd in combination with the "cp" command to copy the Hunger Games.txt document over to my folder.
2. then I renamed the file using "mv" command to "My Hunger Games"
3. Following this, I utilized the Vi utility to edit the document
4. In the Vi interface, I was able to replace the character "Gale" with my name "Stuart" using :1,$s/Gale/Stuart"
The above command did a global replacement from the first line to the last which was the goal of the assignment

I chose Gale as my character to replace due to his stubborness which I can be guilty of sometimes.

#In the case I had to change permissions

If I had to chgrp and chmod in order to adjust permissions, I would use chgrp in the following manner...
--> chgrp [groupname] [fileName] --> this would allow me to change the group of a directory as well as the group name.
--> chmod g+rx [fileName] --> this would specifically allow membders of the "group" cluser read and execute permissions for the specified file.
