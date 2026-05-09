sed is used for line by line operation application on a stream of lines.  
sed 's/oldp/newp' where s is term for substitute.  

sed cannot work on an empty file it needs a stream of lines.  
echo "new-line" >> example.txt is a way to append without any stream.  
echo "new_line" > replaces all content in file.  
echo -e enables special chars like \n.  

Main use of sed IMO would be to replace the occurences of a fucntion call <br>
which was later renamed and then we can use sed instead of replacing every single call.<br>
use /g determitter to replace all occurences of those calls on each line.  
basically gsed -i "s/old_call/new_call/g" example.py.  
