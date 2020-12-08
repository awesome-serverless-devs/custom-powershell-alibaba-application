## PowerShell template for Custom Runtime

### Install

```bash
# Install dependencies in fcfile
$ s install docker -f ./fcfile
```

### Deploy

```bash
$ s deploy
```

### Nas Sync.

```bash
# Sync dependencies to Nas
$ s nas sync .fun/root
```

# Invoke
$ s invoke remote -e "Hello-World"
```