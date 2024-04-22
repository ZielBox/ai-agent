# ai-agent
Performs various AI enabled actions and specialized in security management.

# Compilation Steps
1. Install the go agent on Ubuntu:
```
sudo apt-get update
sudo apt-get install golang
```

2. Initilize the go module
```
shailender@DESKTOP-SEMAA9R:/mnt/c/Users/admin/my-repos/github/ai-agent/source/agent$ go mod init ai-agent
go: creating new go.mod: module ai-agent
go: to add module requirements and sums:
        go mod tidy

shailender@DESKTOP-SEMAA9R:/mnt/c/Users/admin/my-repos/github/ai-agent/source/agent$ ls
ai-agent-main.go  ai-agent.go  go.mod

shailender@DESKTOP-SEMAA9R:/mnt/c/Users/admin/my-repos/github/ai-agent/source/agent$ cat go.mod
module ai-agent

go 1.18
```

3. Start the agent
```
go run main.go
EDR agent started.
2024/04/23 01:29:32 Log file /var/log/syslog streamed to http://example.com/log_receiver successfully
2024/04/23 01:29:33 Log file /var/log/dmesg streamed to http://example.com/log_receiver successfully
^CEDR agent stopped.
```
# Start the Agent

# Testing Agent functionality

# Change log
23/04/2024 - Created draft version of AI Security Agent