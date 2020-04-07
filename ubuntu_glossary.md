# [keyword]: [meaning]

- **alias**: nickname

- **stdout/stdin**: standard output/ standard input (terminal by default)
  - we can chage stdout/stdin (one way is pipe)
  - example: `cmd1[arg1][arg2]...| cmd2[arg1][arg2]...`
    - So, the output of cmd1 travels in the pipe (basically stdout of cmd1 is pipe) and act as an stdin for cmd2, thus we'll see only the ouput of cmd2 in the terminal.
  - stdin/stdout are called as _file descriptors_