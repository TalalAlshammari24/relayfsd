### Go Stack (Best for fast development + simplicity)
## Core CLI App

**cobra** → CLI commands + flags + help pages

**viper** → config file + env vars

**fsnotify** → watch filesystem

**net/http** → HTTP requests

**pkg/sftp** + **golang.org/x/crypto/ssh** → SSH/SFTP

## Logging + UX

**zap** or logrus** → structured logs

**pterm** → beautiful CLI output

## Packaging

**go build -ldflags="-s -w"** → small binary

Easy cross-compile:
```
GOOS=linux GOARCH=amd64 go build
```
