# Airflow install steps

### Install env
* OS: Debian GNU/Linux 10 (buster)
* Database: PostgreSQL 12.2

### Install pip first
> $ sudo apt install python3-pip

### install airflow
> $ sudo pip3 install -i https://mirrors.163.com/pypi/simple/ apache-airflow

### install airflow postgresql backend
> $ sudo pip3 install -i https://mirrors.163.com/pypi/simple/ apache-airflow[postgres]