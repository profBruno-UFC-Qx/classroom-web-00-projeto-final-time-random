[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/IDEzcQ6G)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23435103)
# :checkered_flag: Gradus - Study Tracker Gamificado

Breve descrição do que o seu projeto faz.

## :technologist: Membros da equipe

* 579503 - João Henrique Correia de Sousa - Sistemas de Informação
* 582602 - Antonia Janielly Benicio da Silva - Ciência da Computação

## :bulb: Objetivo Geral

Auxiliar estudantes universitários na organização de suas rotinas de estudo através de técnicas de gamificação, visando reduzir a procrastinação, combater a evasão e incentivar a consistência acadêmica.

## :eyes: Público-Alvo

Estudantes universitários (graduação e pós-graduação).

## :star2: Impacto Esperado

Melhorar o engajamento do aluno com suas responsabilidades diárias, transformando a carga pesada de estudos em uma jornada visualmente recompensadora, fornecendo métricas claras de progresso pessoal.

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

**Usuário Não Logado:** Visitante que acessa apenas a landing page, tela de login e formulário de cadastro.
**User (Estudante):** Usuário autenticado que gerencia exclusivamente suas próprias tarefas, ganha XP e avança de níveis.
**Monitor:** Usuário com permissão de leitura geral para visualizar o ranking de estudantes e acompanhar o progresso das turmas.
**Admin:** Acesso total via painel de controle do Strapi para gerenciar entidades, usuários e configurações do backend.

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação

**Funcionalidades Públicas:**
* Cadastro de novos usuários.
* Autenticação via Login (geração de token JWT).

**Funcionalidades Restritas (Apenas Autenticados):**
* **Dashboard Gamificado:** Visualização do Nível atual, barra de progresso para o próximo nível e XP total acumulado.
* **Gestão de Tarefas (CRUD):** Criar, ler, editar e excluir tarefas de estudo.
* **Mecânica de Recompensa:** Marcar tarefas como concluídas para receber a quantidade de XP predefinida daquela tarefa.
* **Logout:** Encerramento seguro da sessão.

## :spiral_calendar: Entidades ou tabelas do sistema

* **User:** Tabela nativa do Strapi gerenciada pelo plugin Users & Permissions (adicionados campos customizados `xp` e `level`).
* **Task:** Tabela de tarefas acadêmicas, contendo título, descrição, valor de XP, status de conclusão e relacionamento Many-to-One com o User.


----

:warning::warning::warning: As informações a seguir devem ser enviadas juntamente com a versão final do projeto. :warning::warning::warning:


----

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.

**Backend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.


## :shipit: Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Entidade 1 | X |  X  |  | X |
| Entidade 2 | X |    |  X | X |
| Entidade 3 | X |    |  |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | api/entidade1/|
| POST | api/entidade2 |
