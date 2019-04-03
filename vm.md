---
layout: page
title: VM
permalink: /vm/
---

# Download

Baixe a VM [aqui](https://cloud.ufscar.br:8080/v1/AUTH_f93b4feb351e45c1a530d537f1a0c2c7/arq1/vm.tgz).

# Informações de login

* Usuário: `student`
* Senha: `user`

# Licenças

Para usar a licença do Bluespec fora da rede da UFSCar, é necessário conectar-se à VPN.

## Instalando a VPN

Execute os seguintes comandos para instalar a VPN:

```bash
sudo apt update
sudo apt install -y openvpn
wget https://arq1.pmatias.me/static/licencas.ovpn
```

## Usando a VPN

Sempre que for usar a VPN, execute:

```bash
sudo openvpn licencas.ovpn
```

Digite seu **Número UFSCar** e depois sua **senha** quando solicitado.

## Testando

Para verificar se está tudo funcionando com um projeto de teste, execute os seguintes comandos:

```bash
cp -r /opt/bluespec/Bluespec-*/training/BSV/labs/smoke_test .
cd smoke_test
make smoke_test
```

Ao final, deve aparecer a mensagem `Bluespec installation looks OK`.
