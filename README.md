Automatically deploy virtual machines via ansible

squid proxy - automatic configuration of the pc to start caching using squid software containing these components without fail
apt-get install squid-openssl

Install squid. With ansible we change 3 config files squid.conf, openssl.cnf, wgettrc.Generate an OpenSSL private key with the default values (4096 bits, RSA). Generate following self-signed root CA certificate files. Create self-signed certificate OpenSSL. Generate the settings file for the Diffie-Hellman algorithm. Initializing database directories and cache SSL. Change folder permissions /var/spool/squid/ssl_db. Сreate cache_dir. Restart service squid-openssl. To check cache squid using wget, load the config wget.

Checking work via wget
wget https://yandex.ru --no-check-certificate

You need to test on a file, caching will not work on these links
sudo tail -f /var/log/squid/access.log - view the log here
