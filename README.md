# **Projeto Integrador - Modelo**

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

- [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
- [Backend](github.com/marcoandre/pi-backend)
- [Frontend](github.com/marcoandre/pi-frontend)

# **Como usar esse modelo para o Projeto Integrador**

1. Faça um fork desse repositório para a sua conta do GitHub.
2. Clone o repositório para o seu computador.
3. Abra o arquivo README.md no seu editor de texto favorito (recomendamos o [Visual Studio Code](https://code.visualstudio.com/)).
4. Tenha instalada a extensão [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) no seu editor de texto.
5. Edite o arquivo README.md com as informações do seu projeto.

# **Desenvolvimento**

- As equipes serão avaliadas por cada etapa da documentação e entregas realizadas.
- Cada equipe deverá escolher um sistema para o desenvolvimento das atividades, a partir dos modelos apresentados.

# **Modelo de Sistemas: Ordem de Serviço**

- O modelo escolhido permite a contratação de serviços, o que atenderá as necessidades da empresa em questão, assim como a venda de produtos, tudo realizado de forma online.

# **Situação Problema**

![Imagem](docs/Logo.png "Ciclo da Venda")

## Introdução

O grupo de serviços online Sh1roJobs vem atuando na área de jogos há poucos meses, tendo jogadores experientes em sua equipe e oferecendo serviços relacionados a tal como jogar na conta de seus clientes e realizar conquistas no lugar destes. O grupo sente a necessidade de um software que possibilite promover e oferecer seus serviços de modo mais profissional, tendo em vista que realiza todas as suas transações e vendas de forma manual, tratando cliente a cliente. Se tratando de um ramo que tende a receber dezenas de requisições de serviço diariamente, a maneira como se dá atualmente é limitante e inviável, necessitando de uma plataforma para tal.

## Desenvolvimento

O grupo em geral possuí duas formas de gerar capital: a venda de contas e os serviços nos quais seus funcionários jogam na conta do cliente. O primeiro caso é para o cliente que não se importa em deixar suas conquistas pessoais para trás, já o segundo, quando o cliente solicita que a Sh1roJobs atue em sua conta, é para que o cliente mantenha o que já tem porém deseja atingir algum objetivo, então um funcionário da Sh1roJobs irá conquistar tal objetivo no lugar do cliente.

Para realizar a venda de uma conta, o grupo atua da seguinte maneira: baseado em uma relação de confiança é realizado um acordo com o cliente, e então é transferido o valor do pagamento assim como as informações de login. Para a contratação de serviços, o processo é semelhante. Essa forma de negócio possuí brechas para golpes, o que torna o negócio menos rentável do que deveria e acaba atraindo menos clientes, uma forma de contornar tais problemas é utilizar uma plataforma que intermedie a relação com o cliente e o vendedor, porém estas plataformas costumam cobrar uma comissão, reduzindo o lucro sobre o negócio.

## Conclusão

Os problemas apresentados podem ser resolvidos através do desenvolvimento de um software que permita a Sh1roJobs realizar suas vendas e simultâneamente anunciar seus serviços. Tal plataforma pode possibilitar ao cliente o pagamento via pix/cartão de crédito, de forma que a ordem de serviço será emitida após o pagamento, tornando o negócio mais seguro para o grupo. Ao mesmo tempo, possuir uma plataforma online trará mais confiança aos clientes, visto que o serviço será visto de forma mais profissional, já que atuar negociando pessoalmente com cada cliente é desgastante e não permite expandir o negócio de maneira eficiente, visto que é possível criar um sistema onde o cliente é atendido e no final do serviço pode deixar um feedback, atraindo novos clientes.

# **Descrição da proposta**

Após entender o problema, proponha uma solução que será útil nos aspectos de dificuldade encontrados. Assim, aqui você deverá **explicar de maneira resumida, e preferencialmente mais textual, como o software funcionará**. Pense nesse texto como uma **introdução ao seu cliente** do que você pretende fazer por ele, para que ele confirme se realmente está dentro do
desejado e permita sua continuidade.

**Alguns pontos importantes a se destacar são:**

- **Qual o foco de ação do software** relacionado com os problemas levantados na análise da situação-problema. O que realmente o software vai fazer. Por exemplo, o foco de ação do Gmail é permitir o envio e recebimento de e-mails.
- **Os níveis de usuário do sistema**. Somente o gestor tem acesso? E os funcionários? Talvez seja para ambos, ou para funcionários de cargos
  diferentes, etc.
- **O que poderá ser feito no software**.Apenas o principal, sem pensar em
  telas ou detalhes específicos, pois isso será feito em outro momento.
- **Se houver mais de um nível de usuário**, ressaltar as diferenças entre
  eles na descrição da proposta.

O software a principio terá três páginas principais:

- **Página Home**: chamativa, com os feedbacks mais positivos em destaque, e diversas informações chamativas para atrair novos clientes.
- **Página de Vendas**: possibilitará que o grupo Sh1roJobs venda seus produtos virtuais (contas), mostrando todos os anúncios para que os clientes possam adquirir. Também permitirá que vendedores externos anunciem, pagando uma comissão em porcentagem á plataforma no momento da venda.
- **Página de Serviços**: possibilitará que o grupo Sh1roJobs venda seus serviços, mostrando todas as modalidades contratáveis para que os clientes possam selecionar, realizar o pagamento e todo o processo subsequente.

# **Regras de negócio - Requisitos funcionais RF**

## Telas

- PÁGINA INICIAL (Home)

RF01 - Permitir ao visitante entrar em contato com administradores via chat

RF01.1 - A mensagem deverá notificar via email os administradores do site

RF02 - Exibir ao visitante informações de contato

RF03 - Exibir ao visitante as vendas mais recentes

RF04 - Exibir ao visitante quantos serviços estão em progresso no momento

RF05 - Exibir número de acessos ao vivo

- CADASTRO

RF01 - Requisitar ao usuário um nome completo

RF02 - Requisitar ao usuário sua idade

RF03 - Requisitar ao usuário seu email

RF04 - Possibilitar ao usuário inserir seu CPF

RF05 - Para exercer as funções de um usuário verificado, exigir a confirmação do email via verificação

- PÁGINA DE ADMINISTRAÇÃO

RF01 - Exigir autenticação do usuário para acessar a página

RF02 - Exibir todas as reclamações em aberto a partir de clientes

RF03 - Exibir todas as reclamações em aberto a partir de vendedores

RF04 - Exibir relatório de vendas diárias, semanais e mensais

RF05 - Exibir todos os moderadores online no momento

## TIPOS DE USUÁRIO

- USUÁRIO NÃO VERIFICADO

RF01 - Restringir quaisquer alterações de dados de cadastro até que o usuário confirme o email

RF01.1 - Permitir ao usuário trocar o email de verificação da conta

RF02 - O usuário não verificado pode interagir somente como cliente

- USUÁRIO VERIFICADO

RF01 - Permitir que o usuário cadastrado altere sua foto de perfil

RF02 - Permitir que o usuário cadastrado altere seu nome de exibição

RF03 - Restringir do usuário a alteração de quaisquer outros dados de cadastro, apenas via suporte

RF04 - Permitir que o usuário cadastrado delete sua conta

RF05 - O usuário verificado com CPF cadastrado pode interagir como vendedor na página de contas

- MODERADOR

RF01 - A permissão de moderador só pode ser concedida pela administração do site

RF02 - O moderador pode visualizar a área de reclamações em aberto

RF03 - O moderador pode visualizar a área de reclamações em andamento

RF04 - O moderador pode alterar informações de cadastro de usuários comuns

## INTERAÇÕES COM VENDAS E AQUISIÇÕES DE CONTAS

- ANÚNCIO

RF01 - Exigir que o usuário esteja logado com uma conta verificada e com CPF para exercer as funções de anunciante

RF02 - Permitir ao anunciante divulgar uma conta

RF03 - Exigir que anuncio tenha título
RF03.1 - O título deve ter mais de 10 caracteres

RF04 - Exigir que o anúncio tenha descrição

RF04.1 - A descrição deve ter mais de 20 caracteres

RF04.2 - A descrição deve suportar markdown

RF05 - Exigir que o anúncio tenha uma imagem de capa

RF06 - Permitir que o anúncio possua imagens extras

RF07 - Exigir que o anúncio possua um preço em BRL

RF07.1 - O valor do preço não pode conter decimais

- AQUISIÇÃO

RF01 - Exigir que o usuário esteja logado com uma conta, não necessariamente verificada

RF02 - A aquisição de cada conta deve ser feita uma a uma, sem sistema de carrinho

RF03 - Permitir que o usuário realize o pagamento via pix ou cartão de crédito/débito

RF04 - Após confirmar a transação, abrir um chat para que cliente e anunciante se comuniquem e realizem a troca de informações sobre o envio do produto

RF05 - Permitir que o usuário cliente abra uma reclamação solicitando intervenção a administração

RF05.1 - O dinheiro da transação deve ser mantido em carteira durante 15 dias

RF05.1 - As reclamações deverão notificar a administração via email

RF05.2 - Ao abrir uma reclamação, o saldo do vendedor não pode ser sacado temporariamente

RF06 - O comprador pode marcar o produto como recebido

RF06.1 - O vendedor pode marcar o produto como entregue

- INTERAÇÕES COM VENDAS E AQUISIÇÕES DE CONTAS
  ANÚNCIO

RF01 - Em progresso

RF02 - Em progresso

RF03 - Em progresso

RF04 - Em progresso

RF05 - Em progresso

AQUISIÇÃO

RF01 - Em progresso

RF02 - Em progresso

RF03 - Em progresso

RF04 - Em progresso

RF05 - Em progresso

# Regras de negócio - Requisitos não funcionais RNF

RNF 01 - Navegador: O sistema deverá ser compatível com o Google Chrome, Microsoft Edge, Opera e Firefox.

RNF02 - Disponibilidade: O sistema deverá estar disponível 24 horas por dia, 7 dias por semana.

RNF03 - Segurança: O sistema deverá ser seguro, evitando que dados sensíveis dos clientes sejam expostos a terceiros.

RNF04 - Responsividade: O sistema deverá ser responsivo, permitindo que os clientes acessem a loja online de qualquer dispositivo, como computadores, tablets e smartphones.

RNF05 - Desempenho: O software deve ser capaz de processar um número considerado de acessos simultaneamente sem diminuir significativamente o desempenho.

RNF06 - Manutenção: O software deve ser facilmente mantido e atualizado, permitindo que os desenvolvedores adicionem novos recursos sem interromper o funcionamento do site.
