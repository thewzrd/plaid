# PLAID - the GridPane Stack ![CI status](https://img.shields.io/badge/build-passing-brightgreen.svg)

Highly Optimized LEMP7+ Web Server 

This is a 100% non-interactive build of a LEMP stack with customizations specific to the GridPane platform. 

This is currently not meant for outside consumption or use with systems other than GridPane.com provisioned VPS nodes. 

The PLAID stack provides a set of tools and commands that facilitate GridPane powered web server administration.
- Unique commands to create, delete, disable sites.
- Free SSL certificates for your sites with Let’s Encrypt and automatic server configuration.
- HTTP/2 dramatically increase the speed of serving your content.
- PHP v7.2 and support for previous versions if necessary (5.6, 7.0 and 7.1).
- FastCgi Cache and Redis Object Cache for your WordPress sites.
- Get an A+ grade on [Qualys (SSL Labs) Test](https://www.ssllabs.com/ssltest/).
- Log viewer in real time.

### Requirements
* Ubuntu 16.04 or 18.04

## Usage

```bash
# Install PLAID stack
wget -qO gridplaid gridpane.org/gridplaid && sudo bash gridplaid 3 

# Create your first site.
gpsite example.com (requires an active GridPane account)
```

## Documentation
COMING SOON!

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
