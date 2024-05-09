# arr-stack
## Filesystem
This stack uses Docker bind mounts for configuration and requires access to media storage
Create or mount the following structure on the host:

- `~/docker/`
	- `qbittorrent/`
	- `prowlarr/`
	- `sonarr/`
	- `radarr/`
	- `lidarr/`
	- `recyclarr/`
- `/mnt/[local/remote]/`
	- `app_data/`
		- `downloads/`
		- `transcode/`
	- `media/`