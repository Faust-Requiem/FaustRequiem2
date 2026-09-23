# osTicket Prerequisites

Before installing osTicket, the server must have the required
operating system, web server, PHP environment, database server,
and PHP extensions configured.

## Virtual Machine

- Oracle VirtualBox
- Ubuntu Server
- Minimum 2 CPU cores
- Recommended 4 GB RAM
- Recommended 40 GB virtual disk
- Network connectivity

## Web Server

- Apache HTTP Server

## PHP

- Supported PHP version for the selected osTicket release
- PHP CLI
- PHP MySQL/MariaDB support
- Required PHP extensions

## Database

- MySQL or MariaDB
- Database created for osTicket
- Dedicated database user
- Appropriate database privileges

## PHP Extensions

Required/recommended extensions should be verified before
starting the osTicket web installer.

Examples include:

- mysqli
- gd
- imap
- xml
- xml-dom
- json
- mbstring
- intl
- fileinfo
- phar
- apcu
- opcache

## Network

The Ubuntu VM must be able to communicate with the required
package repositories and the administrator must be able to
access the osTicket web interface.

## Verification

Before beginning the osTicket installation, verify:

- [ ] Ubuntu is installed and updated
- [ ] Apache is installed and running
- [ ] PHP is installed
- [ ] Required PHP extensions are installed
- [ ] MariaDB/MySQL is installed and running
- [ ] Database and database user are available
- [ ] Ubuntu has network connectivity
- [ ] osTicket package has been downloaded
