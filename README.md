<h1>Tela Inicial</h1>

A tela inicial é a primeira interface com a qual o usuário interage ao acessar o sistema de gerencia-
mento de tarefas da FIESC. Esta tela apresenta um design simples e amigável, com o objetivo de dar as
boas-vindas aos usuários e direcioná-los para a página de login. Nesta seção, descrevemos os principais
elementos da tela inicial e a estrutura do código HTML.

![1](https://github.com/alexandrepino/Aplicativo_web_fiesc/assets/60200989/23db4fd2-7313-45fd-8a8e-be11cdc7b126)

<h1>Tela Login</h1>

A tela de login é um componente essencial do sistema de gerenciamento de tarefas da FIESC, pois
permite que os usuários acessem suas contas e utilizem as funcionalidades do aplicativo. Nesta seção,
descrevemos os principais elementos da tela de login e a estrutura do código HTML e caso não tenha um
cadastro, abaixo tem um botão que direciona o usuário para a tela de Cadastro.

![2](https://github.com/alexandrepino/Aplicativo_web_fiesc/assets/60200989/1f34a591-565a-4259-b915-60d586031e1f)

<h1>Tela Cadastro</h1>
A tela de cadastro é uma parte importante do sistema de gerenciamento de tarefas da FIESC, pois
permite que novos usuários criem suas contas para acessar e utilizar as funcionalidades do aplicativo.
Nesta seção, apresentamos um resumo dos principais elementos da tela de cadastro, com base no código
HTML fornecido, assim que preenchemos os campos solicitados e apertamos o botão "cadastrar"os dados
preenchidos vão direto para o banco de dados, fazendo assim com que na tela de login o usuário só seja
redirecionado nas outras páginas caso o login e senha estejam cadastrados no banco de dados.

![3](https://github.com/alexandrepino/Aplicativo_web_fiesc/assets/60200989/a05ff539-f87e-4eba-8e20-a924e805ad71)

<h1>Tela Principal</h1>
A tela principal é uma parte essencial do sistema de gerenciamento de tarefas da FIESC, pois apresenta
as funcionalidades disponíveis para os usuários após o login. Nesta seção, apresentamos um resumo dos
principais elementos da tela principal, com base no código HTML fornecido.
Elementos da Tela Principal
A tela Principal é composta pelos seguintes elementos:
• Mensagem de boas-vindas: Exibe uma saudação personalizada, incluindo o nome de usuário da
pessoa conectada.
• Botão Criar nova Tarefa: Um botão que, quando clicado, direciona o usuário para a tela de
criação de uma nova tarefa.
• Botão Logout: Um botão que, quando clicado, efetua o logout do usuário e o direciona para a
tela inicial.
• Tabela de Tarefas: Uma tabela que apresenta as tarefas existentes, incluindo informações como
ID, título, tipo, prioridade, descrição, data de abertura, responsável, status e providência. As linhas
da tabela são destacadas em laranja se o usuário conectado for o responsável pela tarefa.
• Paginação: Exibe a página atual e o total de páginas, e permite a navegação entre as páginas da
tabela de tarefas.
O código HTML apresentado utiliza a biblioteca Bootstrap para criar um layout responsivo e estili-
zado, garantindo uma experiência agradável e funcional aos usuários.

![4](https://github.com/alexandrepino/Aplicativo_web_fiesc/assets/60200989/c9d06dbd-7250-48eb-9fae-088008daa3e0)

<h1>Tela Criar nova Tarefa</h1>
A tela “Criar nova Tarefa” é uma interface do usuário projetada para permitir que os usuários criem
e insiram novas tarefas no sistema. Os elementos visuais da tela incluem:
1. Título da página: Exibe o título “Criar nova Tarefa” no topo da tela.
2. Formulário de criação de tarefa: Contém um formulário com os seguintes campos para preencher
informações da tarefa:
• Título: Campo de texto para inserir o título da tarefa.
• Tipo de problema: Menu suspenso para selecionar o tipo de problema.
• Prioridade: Menu suspenso para selecionar a prioridade da tarefa.
• Descrição: Campo de texto formatado para inserir a descrição detalhada da tarefa.
3. Botões de ação: Apresenta dois botões - um para enviar o formulário para o Banco de Dados e
criar a tarefa e outro para cancelar e voltar à tela anterior.

![5](https://github.com/alexandrepino/Aplicativo_web_fiesc/assets/60200989/63677456-18e8-4b72-b8f0-239c0cf1491c)

<h1>Detalhes da Tarefa</h1>
A tela “Detalhes da Tarefa” é uma interface do usuário projetada para exibir informações detalhadas
sobre uma tarefa específica. Os elementos visuais da tela incluem:
1. Título da página: Exibe o título "Detalhes da Tarefa"seguido pelo ID da tarefa.
2. Informações da tarefa: Apresenta informações sobre a tarefa, como título, responsável, priori-
dade, tipo e data de criação em uma área de conteúdo.
3. Descrição: Exibe a descrição da tarefa em uma área de texto somente leitura.
4. Observações: Lista todas as observações relacionadas à tarefa com a data e hora da postagem.
5. Botões de ação: Contém botões para voltar à lista de tarefas e, se o usuário for o responsável e
a tarefa estiver aberta, um botão para fechar a tarefa.
6. Nova Observação (opcional): Se o usuário for o responsável e a tarefa estiver aberta, exibe um
formulário para adicionar uma nova observação à tarefa e salvar a observação.

![6](https://github.com/alexandrepino/Aplicativo_web_fiesc/assets/60200989/6c11a5d1-0d8a-4038-b048-cf6ce1409307)

<h1>Tela Fechar Tarefa</h1>
A tela "Fechar Tarefa"é uma interface do usuário projetada para permitir que o responsável pela
tarefa feche a tarefa e forneça informações sobre as ações tomadas. Os principais elementos visuais da
tela incluem:
1. Título da página: Exibe o título "Fechar tarefa"seguido pelo título da tarefa.
2. Formulário: Contém um formulário com um campo para inserir detalhes sobre as ações tomadas
para resolver a tarefa.

![7](https://github.com/alexandrepino/Aplicativo_web_fiesc/assets/60200989/3df76db8-97fb-4234-907c-f0f7cb168138)
