# Financial Advisor (Home Assistant add-on repository)

Add-on store entry for the Financial Advisor add-on. This repo holds only the store metadata
(`repository.yaml` and `financial_advisor/config.yaml`). The code and the add-on images are built
from a private repository, which updates this one on every release.

**Do not edit `financial_advisor/config.yaml` here.** It is overwritten on each release.

## Install

1. Settings, Add-ons (Apps), Add-on Store, three-dot menu, Repositories, add
   `https://github.com/canfie1d/financial-advisor-ha-addon`.
2. Install **Financial Advisor** and fill in its options.

## Private images

The images are private on `ghcr.io`. Register a classic personal access token with `read:packages`
with the Supervisor before installing (`POST /docker/registries` with
`{"ghcr.io": {"username": "<github user>", "password": "<token>"}}`).
