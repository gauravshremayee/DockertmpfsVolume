# DockertmpfsVolume

$docker run -d   -it   --name tmptest1   --mount type=tmpfs,destination=/home/parallels/nginx_t   nginx:latest

$ docker container inspect tmptest | grep -i nginx_t

# Option	Description
# tmpfs-size	Size of the tmpfs mount in bytes. Unlimited by default.
# tmpfs-mode	File mode of the tmpfs in octal. For instance, 700 or 0770. Defaults to 1777 or world-writable.
