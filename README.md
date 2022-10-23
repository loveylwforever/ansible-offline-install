![author](https://img.shields.io/badge/author-Hayden-blueviolet.svg)
![license](https://img.shields.io/github/license/ghl1024/ansible-offline-install.svg)
![last commit](https://img.shields.io/github/last-commit/ghl1024/ansible-offline-install.svg)
![issues](https://img.shields.io/github/issues/ghl1024/ansible-offline-install.svg)
![stars](https://img.shields.io/github/stars/ghl1024/ansible-offline-install.svg)
![forks](https://img.shields.io/github/forks/ghl1024/ansible-offline-install.svg)

> 两种安装方式在生产环境的CentOS7系统中已验证通过，适用于**内网离线**或者**外网在线**安装，前提是系统自带或者干净的python环境。

# :smile:安装方式一

```bash
cd /tmp
git clone https://github.com/ghl1024/ansible-offline-install.git
cd ansible-offline-install/ansible
sh install.sh
```

# :smiley:安装方式二

```bash
cd /tmp
wget -c https://github.com/ghl1024/ansible-offline-install/releases/download/V1/ansible-offline-install.tar.gz
tar xf ansible-offline-install.tar.gz
cd ansible
sh install.sh
```

# 依赖版本信息
```
Jinja2-2.10.1.tar.gz

MarkupSafe-1.1.1.tar.gz

PyNaCl-1.3.0.tar.gz

PyYAML-5.1.tar.gz

ansible-2.9.7.tar.gz

asn1crypto-0.24.0.tar.gz

bcrypt-3.1.6.tar.gz

cffi-1.12.3.tar.gz

cryptography-2.6.1.tar.gz

enum34-1.1.8.tar.gz

idna-2.8.tar.gz

install.sh

ipaddress-1.0.22.tar.gz

paramiko-2.4.2.tar.gz

pyasn1-0.4.5.tar.gz

pycparser-2.19.tar.gz

pycrypto-2.6.1.tar.gz

setuptools-41.1.0.zip

simplejson-3.16.0.tar.gz

six-1.12.0.tar.gz
```
