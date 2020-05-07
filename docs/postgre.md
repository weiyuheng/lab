# Install latest postgresql on debian

### env
** Debian GNU/Linux 10 (buster) **

### add postgresql apt repository
> $ echo "deb http://apt.postgresql.org/pub/repos/apt/ buster-pgdg main" | sudo tee /etc/apt/sources.list.d/pgdg.list

### import key and update repository
> $ wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
> $ sudo apt update

### install postgresql
> $ sudo apt install postgresql

### install gui client tool: pgadmin4
> $ sudo apt install pgadmin4