## Requirements

- Uninstall dropbear if previously installed
- Add scripts in `/etc/initramfs-tools`
- Add `authorized_keys` to `/etc/tinyssh-initramfs/authorized_keys` (only ssh-ed25519)
- Add tinysshd flags and optional custom port to `/etc/tinyssh-initramfs/config`
- Profit

## References
- deb package `initramfs-dropbear`
- https://github.com/grazzolini/mkinitcpio-tinyssh/
