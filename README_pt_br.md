# Oficina de Projetos Nº 18

<p align="center">
  <a href="#Desafio">O desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#ArquiteturaAtual">Arquitetura atual</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#ModulosUtilizados">Módulos utilizados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#ProblemasIdentificados">Problemas identificados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#ItensASeremAvaliados">Itens a serem avaliados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#AdministracaoDoProjeto">Administração do Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#AsTecnologias">As tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Contribuidores">Contribuidores</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licenca">Licenca</a>
</p>


## 🚀 O DESAFIO

<p align="justify">A empresa Magazine Upper está planejando migrar seu ERP Odoo de um ambiente on-premise para a Cloud. Uma grande dúvida é qual a melhor cloud utilizada e porque.</p>
<p align="justify">Atualmente, a empresa enfrenta problemas de disponibilidade devido a quedas de energia em seu datacenter e problemas de armazenamento devido ao crescimento dos dados.</p>

## 🎲 ARQUITETURA ATUAL
<p align="justify">- A aplicação está rodando em dois servidores virtuais</p>

- Banco de Dados:
  - 16 vCPUs + 32 GB de memória RAM
  - Banco de dados PostgreSQL com 100 GB de armazenamento

- Aplicação:
  - 16 vCPUs + 32 GB de memória RAM
  - Dados da aplicação ocupando 400 GB de armazenamento

- 600 usuários distribuídos em 30 lojas
- 5 lojas em shoppings
- Todas as lojas se comunicam por VPN


![plot](./diagrams/arquitetura_atual.jpeg)

### 🎲 MÓDULOS UTILIZADOS
- Ecommerce
- Ponto de venda
- Compras
- Vendas
- Financeiro
- Funcionários
- Central de ajuda
- Mensagens
- Dashboard

## 🎲 PROBLEMAS IDENTIFICADOS
- Disponibilidade
  - Quedas de energia no datacenter afetam a disponibilidade
do sistema
- Armazenamento:
  - Crescimento dos dados está além da capacidade do hardware atual
- Custo de Armazenamento:
  - Cotação para um novo disco de storage está em torno de R$ 50.000,00


## 📝 ITENS A SEREM AVALIADOS
[ ] Apresentação - visão de negócio</br>
[ ] Apresentação - detalhes técnicos</br>
[ ] Arquitetura</br>
[ ] Painel de monitoramento com Notificação (discord, telegram, whatsapp, email, SMS)</br>
[ ] Documentação</br>
[ ] Testes</br>
[ ] Participação dos integrantes do grupo</br>
[ ] Demonstração</br>
[ ] Deploy</br>

## 📝 ADMINISTRAÇÃO DO PROJETO
O projeto foi dividido em atividades e gerenciadas usando Kanban e o discord para comunicação e reuniões

## 🛠 AS TECNOLOGIAS
As seguintes tecnologias foram usadas na construção do projeto:
- Terraform
- Oddo
- PostgreSQL
- Docker
- AWS
  -- Outras: Route53, Load Balancing, AutoScaling, Code Build, Co

## ✅ CONTRIBUIDORES

<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/victor-cleber/?locale=en_US"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/13708226?v=4" width="100px;" alt=""/><br /><sub><b>Victor Cleber</b></sub></a><br /></td>
    <td align="center"><a href="https://www.linkedin.com/in/victor-cleber/?locale=en_US"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/13708226?v=4" width="100px;" alt=""/><br /><sub><b>Victor Cleber</b></sub></a><br /></td>

  </tr>
  <tr>
     <td align="center"><a href="https://www.linkedin.com/in/victor-cleber/?locale=en_US"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/13708226?v=4" width="100px;" alt=""/><br /><sub><b>Victor Cleber</b></sub></a><br /></td>
      <td align="center"><a href="https://www.linkedin.com/in/victor-cleber/?locale=en_US"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/13708226?v=4" width="100px;" alt=""/><br /><sub><b>Victor Cleber</b></sub></a><br /></td>
  </tr>
</table>

Happy project 😊

##  🔗 LICENÇA

 <p align="justify">This project is under the GNU General Public License v3.0. See more details in [LICENSE](./LICENSE) for more information.</p>

---