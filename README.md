DESAFIO DE PROJETO DIO
Dia a Dia de um QA: A Prática de Testes Manuais Funcionais
1. Fluxo de Trabalho e Ciclo de Vida do Bug
Fluxo de Trabalho:
Identificação: Registrar o bug no sistema.
Triagem: Avaliar prioridade e gravidade.
Designação: Atribuir a um desenvolvedor.
Investigação e Desenvolvimento: Corrigir o bug.
Revisão e Testes: Validar a correção.
Confirmação da Correção: Validar a solução.
Deploy: Lançar a correção.
Monitoramento: Acompanhar após o lançamento.
1.1 Identificação do Bug
O ciclo começa quando o bug é encontrado, que pode ser feito por qualquer membro da equipe.

Atividades:
Bug é encontrado e registrado no sistema de acompanhamento (ex.: Jira, Trello, GitHub Issues).
Captura de informações relevantes: descrição, passos para reproduzir, gravidade, prioridade, ambiente, capturas de tela, etc.
1.2 Triagem do Bug
Revisão pelo time ou product owner para determinar a importância e o tratamento do bug.

Atividades:
Revisão do bug pelo time ou Scrum Master.
Determinação da gravidade e prioridade.
Verificação se é realmente um bug.
Decisão se será resolvido na sprint atual ou futura.
1.3 Designação
Atribuição do bug a um desenvolvedor que fará a correção, movendo-o para "In Progress" ou equivalente.

Atividades:
Designação a um desenvolvedor.
Discussões técnicas sobre a correção.
Movido para o backlog da sprint ou para a coluna "To Do".
1.4 Investigação e Desenvolvimento
O desenvolvedor analisa o código, reproduz o erro e identifica a causa raiz.

Atividades:
Investigação do código e logs.
Reproduzir o bug.
Criar uma correção.
Realizar testes unitários e de integração.
1.5 Revisão e Testes
Após a correção, o bug é movido para revisão e testes para garantir que o problema foi resolvido.

Atividades:
Revisão de código pelo time.
Testes de QA para verificar se o bug foi corrigido.
Testes automatizados ou manuais.
1.6 Confirmação da Correção
Se a correção passar em todos os testes, o bug é marcado como resolvido.

Atividades:
O bug passa para "Resolved".
Testes finais de validação.
Se novos problemas surgirem, o bug volta para a fase de desenvolvimento.
1.7 Deploy
A correção é implementada na versão de produção.

Atividades:
Deploy da correção.
Comunicação interna sobre a resolução.
Movido para "Closed".
1.8 Monitoramento Pós-Correção
Após o lançamento, o bug deve ser monitorado.

Atividades:
Monitoramento de logs e feedback de usuários.
Verificação de performance.
Se o bug reaparecer, o ciclo reinicia.
2. Users Stories
2.1 KAN
Como usuário, desejo acessar a página de login para criar e autenticar usuário no sistema, bem como realizar operações de recuperação de senha.

Descrição:

Valor: A autenticação é importante para pedidos seguros.
Narrativa do Usuário:
Como: Cliente
Eu quero: acessar a página de login.
Para: visualizar opções de login e cadastro.
Requisitos:
Atores: Cliente.
Interface: Ver documentação anexa UI/UX.
Dados:
Criação de Banco de Dados para armazenar informações dos clientes.
Criação de API para integração com front-end e banco de dados.
Criação da tela de login.
Plataforma/Ambiente: Web/Web Mobile.
Critérios de Aceite:
Usuário visualiza formulário para login.
Usuário visualiza botão de cadastro.
Usuário visualiza botão "esqueci a senha".
2.2 KAN
Como usuário, desejo utilizar a caixa de pesquisa para encontrar produtos.

Descrição:

Valor: A caixa de pesquisa otimiza o tempo do cliente.
Narrativa do Usuário:
Como: Cliente
Eu quero: pesquisar o item desejado.
Para: visualizar uma lista filtrada de produtos.
Requisitos:
Atores: Cliente.
Interface: Ver documentação anexa UI/UX.
Dados:
Criação de API para integração com front-end e banco de dados.
Plataforma/Ambiente: Web/Web Mobile.
Critérios de Aceite:
Usuário visualiza barra de pesquisa.
Usuário digita o item e confirma.
Usuário visualiza lista de produtos filtrados.
2.3 KAN
Como usuário, desejo clicar nos ícones das redes sociais e ser redirecionado aos perfis da loja.

Descrição:

Valor: Perfis sociais permitem interação com a marca.
Narrativa do Usuário:
Como: Cliente
Eu quero: clicar nos ícones das redes sociais.
Para: ser redirecionado para a página correspondente.
Requisitos:
Atores: Cliente.
Interface: Ver documentação anexa UI/UX.
Dados:
Criação de API para redirecionamento.
Plataforma/Ambiente: Web/Web Mobile.
Critérios de Aceite:
Usuário visualiza ícones na loja.
Usuário clica no ícone desejado.
Usuário abre nova aba com o perfil oficial.
3. Documentos
3.1 Casos de Teste: Step by Step
3.1.1 Caso de Teste: Acessar a Página de Login

ID do Caso de Teste: CT001
Título: Verificação do acesso à página de login.
Pré-condições:
Sistema online e acessível.
Navegador compatível.
Ambiente configurado corretamente.
Passos do Teste:
Abrir navegador e acessar a URL.
Resultado Esperado: Página principal exibida.
Clicar em "Login".
Resultado Esperado: Redirecionamento para a página de login.
Verificar formulário de login.
Resultado Esperado: Formulário visível.
Verificar botão "Cadastrar-se".
Resultado Esperado: Botão disponível.
Clicar em "Cadastrar-se".
Resultado Esperado: Redirecionamento para a página de cadastro.
Verificar link "Esqueci minha senha".
Resultado Esperado: Link acessível.
Clicar em "Esqueci minha senha".
Resultado Esperado: Redirecionamento para recuperação de senha.
Inserir e-mail e senha corretos e clicar em "Entrar".
Resultado Esperado: Autenticação bem-sucedida e redirecionamento.
Critérios de Aceite:
Acesso à página de login.
Formulário exibido corretamente.
Botão de cadastro funcional.
Link de recuperação funcional.
Autenticação redireciona para a página principal.
Pós-condições: Usuário logado ou capaz de recuperar senha.
3.1.2 Caso de Teste: Pesquisa de Produtos

ID do Caso de Teste: CT002
Título: Verificação da funcionalidade de pesquisa.
Pré-condições:
Sistema online e acessível.
Navegador compatível.
Ambiente configurado corretamente.
Passos do Teste:
Abrir navegador e acessar a URL.
Resultado Esperado: Página principal exibida.
Verificar presença da barra de pesquisa.
Resultado Esperado: Barra visível com texto.
Clicar na barra e digitar item desejado.
Resultado Esperado: Texto inserido.
Pressionar "Enter" ou clicar no ícone de pesquisa.
Resultado Esperado: Lista de produtos filtrados exibida.
Pesquisar item inexistente.
Resultado Esperado: Mensagem informando que não foram encontrados produtos.
Pesquisar parte do nome de um item.
Resultado Esperado: Lista de produtos com termo parcial.
Realizar pesquisa em dispositivo móvel.
Resultado Esperado: Exibição correta em interface responsiva.
Critérios de Aceite:
Barra de pesquisa visível e funcional.
Resultados correspondentes exibidos corretamente.
