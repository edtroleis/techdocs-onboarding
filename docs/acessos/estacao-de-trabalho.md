# Estação de trabalho

## Requisitos

- Sistema operacional atualizado e com disco criptografado.
- Antivírus/EDR corporativo ativo.
- Bloqueio de tela automático em até 5 minutos.

## Ambiente de desenvolvimento

O ambiente padrão de desenvolvimento é o **OpenShift Dev Spaces**: o ambiente abre no navegador,
já configurado, sem instalar nada na estação. Siga os manuais:

| Manual | Para quê |
|--------|----------|
| [Manual de OpenShift Dev Spaces](http://localhost:3000/docs/default/component/manual-dev-spaces) | **Padrão:** ambiente pronto no navegador |
| [Manual de Podman Desktop](http://localhost:3000/docs/default/component/manual-podman-desktop) | Containers locais |
| [Manual de RHEL](http://localhost:3000/docs/default/component/manual-rhel) | Estações e servidores Red Hat |
| [Manual de WSL](http://localhost:3000/docs/default/component/manual-wsl) | Descontinuado: só para quem ainda usa Linux local no Windows |

!!! warning "Dados sensíveis"
    Não copie dados de produção para a estação de trabalho. Use massas de teste.
