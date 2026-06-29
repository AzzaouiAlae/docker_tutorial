# Docker Tutorial Series

A 10-part, practical introduction to Docker — images, containers, volumes,
networking, Dockerfiles, Compose, env vars, secrets, and the anti-patterns
that quietly break the container model.

## Start here

1. <a href="https://azzaouialae.github.io/docker_tutorial/index.html" target="_blank" rel="noopener noreferrer">What is Docker? Why Docker?</a> — the problem before containers, what an image/container/engine actually are, Docker vs. a VM.
2. <a href="https://azzaouialae.github.io/docker_tutorial/2-images.html" target="_blank" rel="noopener noreferrer">Images</a> — layers, the image cache, tags, registries.
3. <a href="https://azzaouialae.github.io/docker_tutorial/3-containers.html" target="_blank" rel="noopener noreferrer">Containers</a> — lifecycle, namespaces/cgroups, PID 1, restart policies, bootstrapping an app on first start.
4. <a href="https://azzaouialae.github.io/docker_tutorial/4-volumes.html" target="_blank" rel="noopener noreferrer">Volumes</a> — named volumes vs. bind mounts vs. tmpfs, and proving persistence actually survives a recreate.
5. <a href="https://azzaouialae.github.io/docker_tutorial/5-network.html" target="_blank" rel="noopener noreferrer">Network</a> — bridge networks, DNS-based service discovery, `depends_on` vs. readiness.
6. <a href="https://azzaouialae.github.io/docker_tutorial/6-dockerfile.html" target="_blank" rel="noopener noreferrer">Dockerfile</a> — core instructions, layer caching, `CMD` vs. `ENTRYPOINT`, practices that matter.
7. <a href="https://azzaouialae.github.io/docker_tutorial/7-docker-compose.html" target="_blank" rel="noopener noreferrer">Docker Compose</a> — anatomy of `docker-compose.yml`, standalone containers vs. Compose-managed, wrapping Compose in a Makefile.
8. <a href="https://azzaouialae.github.io/docker_tutorial/8-env.html" target="_blank" rel="noopener noreferrer">Env</a> — environment variables and `.env` files.
9. <a href="https://azzaouialae.github.io/docker_tutorial/9-secrets.html" target="_blank" rel="noopener noreferrer">Secrets</a> — file-based secrets, TLS termination at nginx.
10. <a href="https://azzaouialae.github.io/docker_tutorial/10-anti-patterns.html" target="_blank" rel="noopener noreferrer">Anti-Patterns</a> — things that look like they work but defeat the container model (`network: host`, `--link`, infinite-loop entrypoints).

Each page links to the next via the nav bar at the top, so you can also just
start at part 1 and read straight through.
