sed is used for line by line operation application on a stream of lines.  
sed 's/oldp/newp' where s is term for substitute.  

sed cannot work on an empty file it needs a stream of lines.  
echo "new-line" >> example.txt is a way to append without any stream.  
echo "new_line" > replaces all content in file.  
echo -e enables special chars like \n. 