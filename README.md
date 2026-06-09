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
2. Você possui privilégios de **root** (o script verifica isso automaticamente).
3. Há uma conexão ativa com a internet ou interface de rede disponível.

