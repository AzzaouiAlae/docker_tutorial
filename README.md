# Docker Tutorial Series

A 10-part, practical introduction to Docker — images, containers, volumes,
networking, Dockerfiles, Compose, env vars, secrets, and the anti-patterns
that quietly break the container model.

## Start here

1. [What is Docker? Why Docker?](https://azzaouialae.github.io/index.html) — the problem before containers, what an image/container/engine actually are, Docker vs. a VM.
2. [Images](https://azzaouialae.github.io/2-images.html) — layers, the image cache, tags, registries.
3. [Containers](https://azzaouialae.github.io/3-containers.html) — lifecycle, namespaces/cgroups, PID 1, restart policies, bootstrapping an app on first start.
4. [Volumes](https://azzaouialae.github.io/4-volumes.html) — named volumes vs. bind mounts vs. tmpfs, and proving persistence actually survives a recreate.
5. [Network](https://azzaouialae.github.io/5-network.html) — bridge networks, DNS-based service discovery, `depends_on` vs. readiness.
6. [Dockerfile](https://azzaouialae.github.io/6-dockerfile.html) — core instructions, layer caching, `CMD` vs. `ENTRYPOINT`, practices that matter.
7. [Docker Compose](https://azzaouialae.github.io/7-docker-compose.html) — anatomy of `docker-compose.yml`, standalone containers vs. Compose-managed, wrapping Compose in a Makefile.
8. [Env](https://azzaouialae.github.io/8-env.html) — environment variables and `.env` files.
9. [Secrets](https://azzaouialae.github.io/9-secrets.html) — file-based secrets, TLS termination at nginx.
10. [Anti-Patterns](https://azzaouialae.github.io/10-anti-patterns.html) — things that look like they work but defeat the container model (`network: host`, `--link`, infinite-loop entrypoints).

Each page links to the next via the nav bar at the top, so you can also just
start at part 1 and read straight through.
