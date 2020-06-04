This pod serves a static file mounted on empty directory on a node which is running this pod. Also checks for readiness and liveness probes.
Testing:
- deploy pod.yaml
- check if file is created in yout node by doing ssh.
