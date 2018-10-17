# Pomodoro BASH Script

A simple bash script to prompt you to use the pomodoro system. It writes a log
to the local dir and opens your editor to edit the logs after every pomodoro.

## Usage

```bash
$ ./pomodoro
```

Keep it running and go work. After 25 minutes, a dialog will popup (xmessage)
telling you about the pomodoro being over, prompting you to take a break
(clicking yes or no has no effect) then asking you to take notes.

If you accidentally close the terminal or Ctrl-C out, then invoke the script
again giving it the pomodoro number to start at:

```bash
$ pomodoro 5
```

So that it doesn't start from 1 again. Sorry it's just a bash script writing to
a text file and I was too lazy to grep the file for the last pomodoro number


