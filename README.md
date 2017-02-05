# IPTABLES

1. Copy the iptables file on your server

2. Edit the variable `SSH_PORT` if required

3. Move it to folder `/etc/init.d/`

4. Change it permissions to `chmod +x /etc/init.d/iptables`

5. Execute theses rules with `sudo sh /etc/init.d/iptables`

6. Check with `sudo iptables -L`

# FAIL2BAN
