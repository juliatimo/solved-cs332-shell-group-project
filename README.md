Download Link: https://assignmentchef.com/product/solved-cs332-shell-group-project
<br>



The object of this assignment is to gain experience with some advanced programming techniques like process creation and control, file descriptors, signals and possibly pipes. To do this, a team of 5 students will be working together to write their own command shell – much like csh, bsh or the DOS command shell. During the presentation, each student must:

<ul>

 <li>run their part of the code</li>

 <li>talk about their code development difficulties share suggestions to improve their part of codes.</li>

 <li>be ready for 1 question their code</li>

</ul>




Each member the team will write the code for one of the following customized commands:

<ol>

 <li><strong>shell*</strong>: the environment that will execute the rest of the commands. the shell won’t terminate unless the exit command gets executed. The shell displays a different command prompt (i.e. something other than <strong>$</strong> and <strong>&gt;</strong>).</li>

 <li><strong>tree*</strong>: this new command will create a directory and call it Dir0. Then it will change the working directory to Dir0, and create three empty text files namely, t1.txt, t2.txt, t3.txt, and one empty directory, called Dir1, inside it.</li>

 <li><strong>list*</strong>: this new command will clear the terminal screen and print a detailed list of all content of the current directory (like ls -l) to the terminal and <strong>txt</strong>. Finally, it will change the name of text file to <strong>tree.txt</strong>.</li>

 <li><strong>path*</strong>: this new command will print the path of the current directory to the terminal and <strong>txt</strong>, and change the name of text file to <strong>path.txt</strong>. Concatenate the content of <strong>tree.txt</strong> and <strong>path.txt</strong> into <strong>t3.txt</strong> and change the last to <strong>log.txt</strong>. Finally, delete <strong>tree.txt</strong> and <strong>path.txt</strong>.</li>

 <li><strong>exit*</strong>: this new command will print a list the last 4 commands to the terminal, a detailed list of all content of the current directory (like ls -l). Finally, it will wait for the user to hit the “return” key to terminate the shell and return the control to the original shell program on your machine.</li>

</ol>