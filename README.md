# iptables

1. Copy iptables file on your server

2. Edit the variable `SSH_PORT` if required

3. Move him on `/etc/init.d/`

4. Edit his chmod to `chmod +x /etc/init.d/iptables`

5. Execute theses rules with `sudo sh /etc/init.d/iptables`

6. Check with `sudo iptables -L`
