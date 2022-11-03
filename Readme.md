# clamav-mirror-docker

The project runs clamav-mirror.


## About the project
---

Uses the following micro service applications:

-   App clamav-mirror


## Pre-deployment preparation

---

Before deploying the project, install Docker, Docker Compose latest versions.


## Installation

---

**Important!!!**


For installation:
To install, run:

1. Do a git clone.

2. Create an .env file and fill with variables:

```bash
cp ./.env_template ./.env

```

3. Run the project 

Production

```bash
docker-compose -f docker-compose_cloud_DB up -d

```

4. After a couple of minutes, the service will start.


### Useful links

---

[Clamav database repo]( https://github.com/ladar/clamav-data)