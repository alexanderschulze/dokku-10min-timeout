This will set the nginx `proxy_read_timeout` for your dokku app to 10 minutes.

## Installation
```
dokku plugin:install https://github.com/alexanderschulze/dokku-10min-timeout.git
```

previous versions (0.3.x and below) of dokku require a manual process to install plugins
```
cd /var/lib/dokku/plugins
git clone https://github.com/alexanderschulze/dokku-10min-timeout.git
dokku plugins-install
```

