# dockerized-server

Non-static Docker server config as documented in [My dockerized-server Config](https://static.grinnell.edu/blogs/McFateM/posts/042-my-dockerized-server-config).

## Local Development
To use this project "locally", on your workstation, be sure to `git checkout` the `localdomain` branch, and modify your `/etc/hosts` file to reference `traefik.localdomain`.  Also, don't forget to create the `web` network before you spin this up: `docker network create web`.

## dgdockerX Branch
A new `dgdockerX` branch was created on 9-Jan-2020 for purposes of spinning up _Omeka-S_ from https://github.com/Digital-Grinnell/omeka-s2 on node _DGDockerX.grinnell.edu_.

The DNS and stack configurations on _DGDockerX_ should yield the following services and addresses...

  - Omeka-S v2.x @ https://omkea-wmiX.grinnell.edu
  - Traefik dashboard @ http://dgdockerx.grinnell.edu
  - Portainer dashboard @ https://dgdockerx.grinnell.edu/portainer
  - Solr admin dashboard @ https://testx.grinnell.edu
  - PHPMyAdmin dashboard @ https://textlinex.grinnell.edu     
  - WhoAmI report @ https://dgdockerX.grinnell.edu/whoami             
