# Linux_Shell

## Introduction

The shell should have the following features:
- Each job can be identified by either a process ID (PID) or a job ID (JID). The latter is a positive integer assigned by tsh. JIDs are denoted on the command line with the prefix “%”.
- The shell should support the following built-in commands:
–- The quit command terminates the shell.
–- The jobs command lists all background jobs.
–- The bg job command resumes job by sending it a SIGCONT signal, and then runs it in the background. The job argument can be either a PID or a JID.
–- The fg job command resumes job by sending it a SIGCONT signal, and then runs it in the foreground. The job argument can be either a PID or a JID.
- If the command line ends with an ampersand (&), then the shell should run the job in the background. Otherwise, it should run the job in the foreground. When starting a background job, the shell should print out the command line, prepended with the job ID and the process ID.
- The shell should be able to handle SIGINT and SIGTSTP appropriately. If there is no foreground job, then these signals should have no effect.
- The shell should reap all of its zombie children. If any job terminates or stops because it receives a signal that it didn’t catch, then the shell should recognize that event and print a message with the job’s JID and PID, and the offending signal number.
- The shell should support I/O redirection.
- The shell should be able to redirect the output from the built-in jobs command.

## Password protected zip

Contact `albertlin0129@gmail.com`
