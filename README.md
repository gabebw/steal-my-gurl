# Everybody wanna steal my (g)url

This is deployed on at http://steal-my-gurl.gabebw.com

## Deployment

It runs via nginx on
[my Digital Ocean droplet](https://cloud.digitalocean.com/projects/72d7f367-f6a4-4a47-b7d0-2e5d1b27bc26/resources?i=b5b934).

To deploy a new version, run:

    bin/deploy

It assumes you have a setting for `i` in `~/.ssh/config`, like:

    Host i
        HostName i.gabebw.com
        Port 13425
        User gabe
