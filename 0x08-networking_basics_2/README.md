0. Change your home IP

0-change_your_home_IP - Write a Bash script that configures an Ubuntu server with the below requirements.

Requirements:

- localhost resolves to 127.0.0.2
- facebook.com resolves to 8.8.8.8.
- The checker is running on Docker, so make sure to read this

In this example we can see that:

- before running the script, localhost resolves to 127.0.0.1 and facebook.com resolves to 157.240.11.35
- after running the script, localhost resolves to 127.0.0.2 and facebook.com resolves to 8.8.8.8

If you’re running this script on a machine that you’ll continue to use, be sure to revert localhost to 127.0.0.1. Otherwise, a lot of things will stop working!



1. Show attached IPs

1-show_attached_IPs - Write a Bash script that displays all active IPv4 IPs on the machine it’s executed on.

Example:

sylvain@ubuntu$ ./1-show_attached_IPs | cat -e
10.0.2.15$
127.0.0.1$
sylvain@ubuntu$
Obviously, the IPs displayed may be different depending on which machine you are running the script on.

Note that we can see our localhost IP :)
