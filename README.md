Task 1 : Basic Task

ls
pwd
mkdir workspace
cd workspace
ls
touch README.md
cp README.md CHANGELOG.md

Task 2 : Absolte and Relative Paths

touch exercise.md
mv exercise.md ../../../tmp
rm -i /tmp/exercise.md

Task 3 : Cat Commands

touch umuzi.md recruits.md cohort.md
echo "Greate powers requires greate resposibiliy." > recruits.md
echo "I can control minds." > cohort.md 
echo "I have superpowers!" > umuzi.md
cat umuzi.md recruits.md cohort.md
cat umuzi.md recruits.md cohort.md >> summary.md
echo “The End” >> summary.md

Task 4 : The locate command

echo | locate umuzi >> search_result.md

Task 5 : The locate command cont..

touch Documents/pad.md
cd Desktop/ &&  touch work
cp ~/Documents/pad.md ./pad_copy.md
locate updatedb
cd ~
locate pad_copy.md

Task 6 : Find commands


locate "*pdf"
locate "*pdf" >> myPDFs.md
find ~ -type f -mtime -1

Task 7 : Test Editor
nano my_bio.md
mkdir my_files | mv my_bio.md my_files/
