# gentoo_helper

Este é um script em Shell Bash desenvolvido para automatizar a instalação básica do Gentoo Linux de forma rápida e prática, configurado sob medida para o usuário [**zLuuzis**](https://github.com/zLuuzis).

## 🚀 Funcionalidades

- Configuração de rede automatizada (via `nmtui` ou `nmcli`).
- Particionamento interativo com `cfdisk`.
- Formatação e montagem automática de partições.
- Otimização do `make.conf` (suporte a processadores nativos e placa de vídeo NVIDIA).
- Sincronização automatizada do Portage e Binhost.
- Instalação automatizada do Kernel (`gentoo-kernel-bin`) e ferramentas essenciais.
- Configuração de usuários, hostname e serviços iniciais (OpenRC).

## ⚠️ Pré-requisitos

Antes de rodar o script, certifique-se de que:
1. Você iniciou o computador através da ISO oficial de instalação do Gentoo.
2. Você esteja rodando em usuário **root** (o script verifica isso automaticamente).
3. Há uma conexão ativa com a internet ou interface de rede disponível.

## ⚖️ Licença

Este projeto está sob a licença GNU/GPL v3.0 - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

# gentoo_helper

This is a Bash Shell script developed to automate the basic installation of Gentoo Linux quickly and practically, custom-configured for the user [**zLuuzis**](https://github.com/zLuuzis).

## 🚀 Features

- Automated network configuration (via `nmtui` or `nmcli`).
- Interactive partitioning with `cfdisk`.
- Automatic formatting and mounting of partitions.
- `make.conf` optimization (support for native processors and NVIDIA graphics cards).
- Automated Portage and Binhost synchronization.
- Automated installation of the Kernel (`gentoo-kernel-bin`) and essential tools.
- Configuration of users, hostname, and initial services (OpenRC).

## ⚠️ Prerequisites

Before running the script, make sure that:
1. You booted the computer using the official Gentoo installation ISO.
2. You are running as the **root** user (the script checks this automatically).
3. There is an active internet connection or an available network interface.

## ⚖️ License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
