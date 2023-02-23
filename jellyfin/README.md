
## Open Media Vault 6
- Install Proxmox-Kernel, via Plugin openmediavault-kernel. Tested with 5.19.17-2-pve
- Download ehl_guc_70.1.1.bin from ehl_guc_70.1.1.bin and copy to /lib/firmware/i915
- Install VAAPI-Driver: `apt install intel-media-va-driver`
- Install VA-Tools (optional, for troubleshooting) `apt install vainfo intel-gpu-tools`
- Add i915.enable_guc=2 i915.force_probe=4e61 to /etc/default/grub in GRUB_CMDLINE_LINUX_DEFAULT=""
- Update grub: `update-grub`
- Reboot system

## Jellyfin
- Activate Hardware-Transcoding
<img width="827" alt="Jellyfin Transcoding" src="https://user-images.githubusercontent.com/78471292/220912606-059ea87f-f051-485f-9050-ab0cd2815538.png">
