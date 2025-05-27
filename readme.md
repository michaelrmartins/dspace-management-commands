# DSpace 8 - Scripts de Gerenciamento

Este repositório contém scripts para facilitar o gerenciamento da aplicação DSpace 8 Angular e seus serviços relacionados. Abaixo está a descrição de cada comando disponível em `/usr/local/sbin/`:

## Comandos Disponíveis

| Comando                  | Descrição                                                                                   |
|--------------------------|---------------------------------------------------------------------------------------------|
| **dspace-dev**           | Inicia a aplicação DSpace 8 Angular em modo desenvolvimento, aumentando o limite de memória do Node.js. |
| **dspace-help**          | Exibe um menu de ajuda listando todos os comandos disponíveis e suas descrições.            |
| **dspace-rebuild**       | Recompila a aplicação DSpace 8 Angular e reinicia o processo usando o PM2.                  |
| **dspace-restart-all**   | Reinicia todos os serviços do DSpace 8 (PostgreSQL, Solr, Tomcat) e recompila a aplicação Angular. |
| **dspace-restart-services** | Reinicia apenas os serviços do DSpace 8 (PostgreSQL, Solr, Tomcat) sem recompilar a aplicação. |
| **dspace-start**         | Inicia a aplicação DSpace 8 Angular usando o PM2.                                           |
| **dspace-stop**          | Finaliza a aplicação DSpace 8 Angular.                                                      |

## Recomendações

- Todos os scripts possuem comentários explicativos na quarta linha para facilitar a identificação no menu de ajuda.
- Recomenda-se utilizar o comando `dspace-help` para visualizar rapidamente as funções de cada script.

---

**Autor:** Michael Martins  
**Data:** 2025-05-20

![forthebadge](https://forthebadge.com/images/badges/works-on-my-machine.svg)
