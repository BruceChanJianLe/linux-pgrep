# Linux PGrep
  
This repository demonstrates the usage of Linux pgrep command.

## Usage
```bash
# Long output
pgrep -l

# User own
pgrep -u

pgrep systemd
```

## Examples
```example
       Example 1: Find the process ID of the named daemon:

              $ pgrep -u root named

       Example 2: Make syslog reread its configuration file:

              $ pkill -HUP syslogd

       Example 3: Give detailed information on all xterm processes:

              $ ps -fp $(pgrep -d, -x xterm)

       Example 4: Make all netscape processes run nicer:

              $ renice +4 $(pgrep netscape)

       Example 5: List all process in detail from user id 1000:

              $ pgrep -l -u 1000
```

## Reference
- [link_youtube](https://www.youtube.com/watch?v=-nRozQcv13I)
