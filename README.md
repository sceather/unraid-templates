# Unraid Templates
- ### [Dockhand](#dockhand)

----
### **```Dockhand```**

Dockhand is a modern, efficient Docker management application providing real-time container management, Compose stack orchestration, and multi-environment support.

### Features
* Container Management: Start, stop, restart, and monitor containers in real-time
* Compose Stacks: Visual editor for Docker Compose deployments
* Git Integration: Deploy stacks from Git repositories with webhooks and auto-sync
* Multi-Environment: Manage local and remote Docker hosts
* Terminal & Logs: Interactive shell access and real-time log streaming
* File Browser: Browse, upload, and download files from containers
* Authentication: SSO via OIDC, local users, and optional RBAC (Enterprise)

https://github.com/Finsys/dockhand<br/>
https://dockhand.pro/manual/#
<br/>
<br/>
**[🔼 Back to top](#unraid-templates)**

----


## docker-compose

By default, no environment variables or volume mounts are required to deploy the container:

```yaml
services:
  selfhst-icons:
    image: ghcr.io/selfhst/icons:latest
    container_name: selfhst-icons
    restart: unless-stopped
    ports:
      - 4050:4050
```

Additional customization can be achieved through several optional variables and volume mounts:


