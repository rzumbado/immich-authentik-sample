# immich and Authentik Integration Sample Project

## Tutorial
Here is the tutorial link that references this test git repo:
https://dev.to/rzumbado/immich-sso-with-authentik-2gi9

## Setup the test environment

I separated authentik and immich configurations on purpose so you can see how each app is configured thru docker compose.

run the following to run athentik:
```bash
cd authentik
docker compose up -d
```

run the following to run immich:
```bash
cd immich
docker compose up -d
```