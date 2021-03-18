# Shell Project with Cosmin Bejan and Drobnitchi Daniel

As a project work of our Operating System course we have implemented this basic shell program for Linux / Unix like operating system.

<h2> What can we do with it? </h2>
<ol>
  <li>Program runs in an infinite loop in which it prints a command prompt, accepts a command, executes the command, and prints the prompt for the next command.</li>
  <li>Input/output redirection (>, <)</li>
  <li>Basic pipes (|)</li>
  <li>Both internal commands (ls, pwd, cd etc.) and external commands (using execvp system call)</li>
  <li>Command history (typing "history" will give entire command history), Uparrow and Downarrow key for command history navigation</li>
  <li>"echo" command</li>
  <li>Handling user interrupt signal (SIGINT)</li>
  <li>Print current date and time.</li>
</ol>
<h2> References </h2>
<ol> 
  <li>Man pages of following system calls: wait, dup2, fork, execvp, chdir.</li>
  <li>GNU readline library documentation (https://tiswww.case.edu/php/chet/readline/readline.html)</li>
  <li>GNU history library documentation (https://tiswww.case.edu/php/chet/readline/history.html)</li>
  <li>A very basic shell implemented by Stephen Brennan. (https://brennan.io/2015/01/16/write-a-shell-in-c/).</li>
  <li>The course by our Proffesor Paul Irofti (https://cs.unibuc.ro/~pirofti/so.html).</li>
</ol>
