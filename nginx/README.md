It is a nginx config file .

### start

~~~
systemctl start nginx
systemctl enable nginx
~~~

### reload

~~~
systemctl reload nginx
~~~

## ufw

~~~
ufw enable
ufw disable

ufw status
ufw status verbose

ufw allow 443/tcp
ufw delete allow 443/tcp
~~~