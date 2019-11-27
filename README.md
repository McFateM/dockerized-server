# dockerized-server

Non-static Docker server config as documented in [My dockerized-server Config](https://static.grinnell.edu/blogs/McFateM/posts/042-my-dockerized-server-config).

## Local Development
To use this project "locally", on your workstation, be sure to `git checkout` the `localdomain` branch, and modify your `/etc/hosts` file to reference `traefik.localdomain`.  Also, don't forget to create the `web` network before you spin this up: `docker create network web`.
