# Kubectl switch version plugin
Switch over kubectl versions very easily without any headache either command to remember.

## Getting started
```bash
kubectl switch version v1.16.10
```

## Installation
```bash
chmod +x kubectl-switch
cp kubectl-switch /usr/local/bin
```

## Commands

### Helper
Print the usage helper:
```bash
kubectl switch help
```

### Show commands
Show the plugin version:

```bash
kubectl switch show version
```

Show the current value for `KUBECONFIG`:

```bash
kubectl switch show config
```

### Switch version
```bash
kubectl switch version v1.18.0
```
If the requested version does not exist it will download it and configure it.

Otherwise you will only select the expected version.
