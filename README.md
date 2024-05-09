# arr-stack


### Filesystem
This stack uses Docker bind mounts for configuration and requires access to media storage.
Create the following structure on the host:

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
	- `media/`

### Environment variables
Environment variables are used for application configuration, the following variables must be set. An example .env file is included in this repository for reference.

| Environment variable | Value                          |
| -------------------- | ------------------------------ |
| PUID                 | User ID                        |
| PGID                 | Group ID                       |
| TZ                   | Timezone                       |
| CDATA                | Container storage location     |
| ADATA                | Application storage location   |