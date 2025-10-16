## Prerequisite
This already assumes Proxmox is installed on the hardware.

Tools:
- Rufus
- Proxmox

## Initial Configurations
When you first open Proxmox, you will get a pesky subscription notification. We will turn this notification off permanently.

To do so, we can SSH into the Proxmox server using any SSH tools like MobaXterm or PuTTY. I will use the Command Prompt to SSH into my Proxmox server.

In Command prompt, Run the command:
```bash
ssh [PROXMOX_SERVER_IP_ADDRESS] -l root
```

Where PROXMOX_SERVER_IP_ADDRESS is the IP address of the Proxmox server.