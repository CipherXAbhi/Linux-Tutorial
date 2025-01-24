## Linux Commands

<table style="width:100%;">
  <tr>
    <th>S.No</th>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>1.</td>
    <td>pwd</td>
    <td>(present working directory) check your current location.</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>whoami</td>
    <td>Display name of current logged-in user.</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>date</td>
    <td>Check System date or time</td>
  </tr>
  <tr>
    <td>4.</td>
    <td>date +%D | date +%T | date +%H:%M</td>
    <td>Check System date only, Check System Time only, Customize format hours & Minutes</td>
  </tr>
  <tr>
    <td>5.</td>
    <td>ls , ls -lt , ls -ltr , ls -lh</td>
    <td>display files and directory present in current location.(ls -lt ) file and folder full information. (ls -lh) human redable.</td>
  </tr>
  <tr>
    <td>6.</td>
    <td>cat filename</td>
    <td>display content of the file on terminal.</td>
  </tr>
  <tr>
    <td>7.</td>
    <td>less filename</td>
    <td>Read file and search for a word.(open file with less command. when open file type <b>/abhi</b> search this name in the file.), <b>shift+g</b> for search to bottom, press <b>q</b> to quit the from the file.</td>
  </tr>
  <tr>
    <td>8.</td>
    <td>more filename</td>
    <td>view content of the file  page by page.</td>
  </tr>
  <tr>
    <td>9.</td>
    <td>touch filename</td>
    <td>Create a file in linux.</td>
  </tr>
  <tr>
    <td>10.</td>
    <td>rm filename</td>
    <td>delete a file in linux</td>
  </tr>
   <tr>
    <td>11.</td>
    <td>vi filename, nano filename</td>
    <td>edit a file in linux.(vi insert the content type i, when complete the editing type esc. and then press shift+:wq)</td>
  </tr>
   <tr>
    <td>12.</td>
    <td>mkdir filename</td>
    <td>create a directory/folder in linux.</td>
  </tr>
   <tr>
    <td>13.</td>
    <td>rmdir</td>
    <td>remove directory</td>
  </tr>
  <tr>
    <td>14.</td>
    <td>cd</td>
    <td>change path and move to another directory. cd Downloads/Privatefolder, example : suppose that you are in the directory Downloads/privatefolder/keysfolder/ now i wnat to jumo on the previous folder (cd ..), jump from two locations (cd ../..), root directory (cd /)</td>
  </tr>
  <tr>
    <td>15.</td>
    <td>cp filename /dest/path </td>
    <td>copy and paste a file from one folder to another in Linux. copy the file from the previous directory and paste in the present directory using this command (cp ../sortdemo.txt .) dot use for present directory. Copy same file in the same directory using this command (cp sortdemo.csv sortdemo_copy.csv)</td>
  </tr>
   <tr>
    <td>16.</td>
    <td>mv filename /dest/path</td>
    <td>move file or directory</td>
  </tr>
   <tr>
    <td>17.</td>
    <td>head -5 filename</td>
    <td>read or display top 5 lines from a file in linux.</td>
  </tr>
  <tr>
    <td>18.</td>
    <td>tail -5 filename</td>
    <td>read or display bottom 5 lines from a file in linux</td>
  </tr>
  <tr>
    <td>19.</td>
    <td>sort filename, sort -r filename</td>
    <td>SORT the content from a file in linux. -r for reverse sort z to a</td>
  </tr>
  <tr>
    <td>20.</td>
    <td>sort filename | uniq</td>
    <td>display UNIQUE content from a file in linux. note down first sort the file than use uniq</td>
  </tr>
  <tr>
    <td>21.</td>
    <td>split -l 3 filename</td>
    <td>A file has 9 lines. split this file in 3 diffenent files in linux.</td>
  </tr>
  <tr>
    <td>22.</td>
    <td>grep "word" filename</td>
    <td>search a word and display matching content from a file in Linux.</td>
  </tr>
  <tr>
    <td>23.</td>
    <td>egrep "word1|word2" filename</td>
    <td>search multiple words and display matching content from a file in Linux.</td>
  </tr>
  <tr>
    <td>24.</td>
    <td>ls file* , touch file{1..5}</td>
    <td>wildcards in linux. (ls x*) it shows all the file which name starts with x, (ls *.csv). I want to make a multiple files (touch filename(1..10)</td>
  </tr>
  <tr>
    <td>25.</td>
    <td>wc -l filename</td>
    <td>count no. of lines in a file.</td>
  </tr>
  <tr>
    <td>26.</td>
    <td>cmp filename1 filename2</td>
    <td>check the two files are identical or not in linux.</td>
  </tr>
  <tr>
    <td>27.</td>
    <td>diff -u filenameA filenameB</td>
    <td>Compare and display diffenrent between two files in linux.</td>
  </tr>
  <tr>
    <td>28.</td>
    <td>find /path/ -name filename</td>
    <td>find a file in linux</td>
  </tr>
  <tr>
    <td>29.</td>
    <td>updatedb, locate filename</td>
    <td>find a file in linux. first update the db and then locate file</td>
  </tr>
  <tr>
    <td>30.</td>
    <td>history, history | grep sort</td>
    <td>display previously used commands in past.</td>
  </tr>
  <tr>
    <td>31.</td>
    <td>history</td>
    <td>display previously used commands in past.</td>
  </tr>
  <tr>
    <td>32.</td>
    <td>help command, ls --help, ls --help | more</td>
    <td>display previously used commands in past.</td>
  </tr>
  <tr>
    <td>33.</td>
    <td>man ls</td>
    <td>read or get more info about a command.</td>
  </tr>
  <tr>
    <td>34.</td>
    <td>which ls/td>
    <td>check which executable is using for a command.</td>
  </tr>
  <tr>
    <td>35.</td>
    <td>script</td>
    <td>record your activity on terminal in a file.</td>
  </tr>
   <tr>
    <td>36.</td>
    <td>script</td>
    <td>record your activity on terminal in a file.</td>
  </tr>
   <tr>
    <td>37.</td>
    <td>alias l="ls -ltr"</td>
    <td>create a short-cut of a long command in linux.</td>
  </tr>
   <tr>
    <td>38.</td>
    <td>gzip -k filename</td>
    <td>compress </td>
  </tr>
  
</table>
