# WorkTasks

Aplicação desenvolvida em **Microsoft Power Apps** para gestão de atividades e tarefas, centralizando responsáveis, prazos, status e acompanhamento da execução operacional.

---

## Objetivo

O **WorkTasks** foi criado para organizar atividades e tarefas em um único ambiente, permitindo acompanhar execução, responsáveis, vencimentos e vínculos entre diferentes itens de trabalho.

A solução busca reduzir controles paralelos e dar maior visibilidade sobre o andamento das atividades.

---

## Principais funcionalidades

- Cadastro e edição de atividades
- Cadastro, edição e exclusão de tarefas
- Associação de tarefas às atividades
- Definição de responsáveis
- Controle de vencimento
- Controle de status
- Replicação de tarefas para outros responsáveis
- Vinculação com projetos e demandas
- Consulta e gerenciamento das atividades registradas
- Visualização em Kanban
- Integração com usuários do Microsoft 365

---

## Telas da aplicação

### Início

Tela inicial para navegação entre os principais módulos da aplicação.

### Registro

Cadastro de novas atividades e tarefas.

### Gerenciamento

Consulta, edição e gerenciamento das atividades e tarefas existentes.

### Relatórios

Visão consolidada das atividades para acompanhamento operacional.

### Kanban de Tarefas

Visualização das tarefas por status para facilitar o acompanhamento da execução.

### Configurações

Área destinada às configurações e parâmetros utilizados pela aplicação.

---

## Arquitetura

A solução segue o fluxo:

**Usuário**  
↓  
**Power Apps Canvas App**  
↓  
**Atividades e Tarefas**  
↓  
**Fonte de Dados**  
↓  
**Automações e Integrações**  
↓  
**Acompanhamento Operacional**

---

## Tecnologias

`Microsoft Power Apps` · `Power Fx` · `Microsoft 365` · `SharePoint` · `Power Automate` · `YAML` · `Canvas Apps`

---

## Estrutura do projeto

O projeto utiliza o formato de código-fonte do Power Apps baseado em arquivos `*.pa.yaml`.

```text
Src/
├── App.pa.yaml
├── Screen1.pa.yaml
├── scrConfiguracoesV8.pa.yaml
├── scrGerenciarV8.pa.yaml
├── scrInicioV8.pa.yaml
├── scrKanbanTarefasV8.pa.yaml
├── scrRegistroV8.pa.yaml
└── scrRelatoriosV8.pa.yaml
```

Cada arquivo representa uma tela ou componente da aplicação, permitindo controle de versão e acompanhamento das alterações realizadas no projeto.

---

## Diferenciais

- Centralização de atividades e tarefas
- Gestão de responsáveis e prazos
- Navegação entre atividade e tarefas relacionadas
- Visualização operacional por Kanban
- Estrutura preparada para integração com Microsoft 365
- Versionamento do código-fonte em Git
- Evolução contínua da aplicação

---

## Privacidade e confidencialidade

O repositório é utilizado para versionamento técnico da solução.

Dados, conexões, credenciais, URLs internas, informações corporativas e dados pessoais não devem ser publicados ou armazenados no repositório público.

---

## PS Qualidade

Projeto desenvolvido pela **PS Qualidade**.

🌐 [psqualidade.com.br](https://psqualidade.com.br)

**Dados e processos conectados.**
