# Reverse shell using go

Change the ip and port to required values.

# Build

env GOOS=windows GOARCH=386 go build hello.go

The env command runs a program in a modified environment. This lets you use environment variables for the current command execution only. The variables are unset or reset after the command executes.

The following table shows the possible combinations of GOOS and GOARCH you can use:

GOOS - Target Operating System	GOARCH - Target Platform

| GOOS - Target Operating System | GOARCH - Target Platform |
|--------------------------------|--------------------------|
| android                        | arm                      |
| darwin                         | 386                      |
| darwin                         | amd64                    |
| darwin                         | arm                      |
| darwin                         | arm64                    |
| dragonfly                      | amd64                    |
| freebsd                        | 386                      |
| freebsd                        | amd64                    |
| freebsd                        | arm                      |
| linux                          | 386                      |
| linux                          | amd64                    |
| linux                          | arm                      |
| linux                          | arm64                    |
| linux                          | ppc64                    |
| linux                          | ppc64le                  |
| linux                          | mips                     |
| linux                          | mipsle                   |
| linux                          | mips64                   |
| linux                          | mips64le                 |
| netbsd                         | 386                      |
| netbsd                         | amd64                    |
| netbsd                         | arm                      |
| openbsd                        | 386                      |
| openbsd                        | amd64                    |
| openbsd                        | arm                      |
| plan9                          | 386                      |
| plan9                          | amd64                    |
| solaris                        | amd64                    |
| windows                        | 386                      |
| windows                        | amd64                    |
|                                |                          |
