# Estação de trabalho

## Requisitos

- Sistema operacional atualizado e com disco criptografado.
- Antivírus/EDR corporativo ativo.
- Bloqueio de tela automático em até 5 minutos.

## Ambiente de desenvolvimento

O ambiente padrão em estações Windows é o **WSL2**. Para começar sem instalar nada, use o
**OpenShift Dev Spaces**: o ambiente abre no navegador. Siga os manuais:

| Manual | Para quê |
|--------|----------|
| [Manual de WSL](http://localhost:3000/docs/default/component/manual-wsl) | Linux no Windows |
| [Manual de Podman Desktop](http://localhost:3000/docs/default/component/manual-podman-desktop) | Containers locais |
| [Manual de RHEL](http://localhost:3000/docs/default/component/manual-rhel) | Estações e servidores Red Hat |
| [Manual de OpenShift Dev Spaces](http://localhost:3000/docs/default/component/manual-dev-spaces) | Ambiente pronto no navegador, sem instalar nada |

!!! warning "Dados sensíveis"
    Não copie dados de produção para a estação de trabalho. Use massas de teste.
