# **ShiroJobs**
![Imagem](docs/Logo.png "Ciclo da Venda")

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

- [Documentação (esse documento)](github.com/TheSh1ro/documentedSh1roJobs)
- [Backend](https://github.com/TheSh1ro/shiroBackend)
- [Frontend](https://github.com/TheSh1ro/vueShiro)
- [App](https://github.com/TheSh1ro/reactShiro)

# **Modelo de Sistemas: Ordem de Serviço**

- O modelo escolhido permite a contratação de serviços, o que atenderá as necessidades da empresa em questão, assim como a venda de produtos, tudo realizado de forma online.

## Introdução

O grupo de serviços online **Sh1roJobs** vem atuando na área de jogos há poucos meses, tendo jogadores experientes em sua equipe e oferecendo serviços relacionados a tal como jogar na conta de seus clientes e realizar conquistas no lugar destes. O grupo sente a necessidade de um software que possibilite promover e oferecer seus serviços de modo mais profissional, tendo em vista que realiza todas as suas transações e vendas de forma manual, tratando cliente a cliente. Se tratando de um ramo que tende a receber dezenas de requisições de serviço diariamente, a maneira como se dá atualmente é limitante e inviável, necessitando de uma plataforma para tal.

## Desenvolvimento

O grupo em geral possui duas formas de gerar capital: a **venda de contas** e os **serviços** nos quais seus funcionários jogam na conta do cliente. O primeiro caso é para o cliente que não se importa em deixar suas conquistas pessoais para trás, já o segundo, quando o cliente solicita que a Sh1roJobs atue em sua conta, é para que o cliente mantenha o que já tem porém deseja atingir algum objetivo, então um funcionário da Sh1roJobs irá conquistar tal objetivo no lugar do cliente.

Para realizar a venda de uma conta, o grupo atua da seguinte maneira: baseado em uma relação de confiança é realizado um acordo com o cliente, e então é transferido o valor do pagamento assim como as informações de login. Para a contratação de serviços, o processo é semelhante. Essa forma de negócio possuí brechas para golpes, o que torna o negócio menos rentável do que deveria e acaba atraindo menos clientes, uma forma de contornar tais problemas é utilizar uma **plataforma que intermedie** a relação com o cliente e o vendedor, porém estas plataformas costumam cobrar uma comissão, reduzindo o lucro sobre o negócio.

## Conclusão

Os problemas apresentados podem ser resolvidos através do desenvolvimento de um software que permita a Sh1roJobs realizar suas vendas e simultâneamente anunciar seus serviços. Tal plataforma pode possibilitar ao cliente o pagamento via pix/cartão de crédito, de forma que a ordem de serviço será emitida após o pagamento, tornando o negócio mais seguro para o grupo. Ao mesmo tempo, possuir uma plataforma online trará mais confiança aos clientes, visto que o serviço será visto de forma mais profissional, já que atuar negociando pessoalmente com cada cliente é desgastante e não permite expandir o negócio de maneira eficiente, visto que é possível criar um sistema onde o cliente é atendido e no final do serviço pode deixar um feedback, atraindo novos clientes.

<!--
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
!-->

O software a principio terá três páginas principais:

- **Página Home**: chamativa, com os feedbacks mais positivos em destaque, e diversas informações chamativas para atrair novos clientes.
- **Página de Vendas**: possibilitará que o grupo Sh1roJobs venda seus produtos virtuais (contas), mostrando todos os anúncios para que os clientes possam adquirir. Também permitirá que vendedores externos anunciem, pagando uma comissão em porcentagem á plataforma no momento da venda.
- **Página de Serviços**: possibilitará que o grupo Sh1roJobs venda seus serviços, mostrando todas as modalidades contratáveis para que os clientes possam selecionar, realizar o pagamento e todo o processo subsequente.

# **Regras de negócio - Requisitos funcionais RF**

## Telas

- PÁGINA INICIAL (Home)

RF1 - Permitir ao visitante entrar em contato com administradores via chat

RF1.1 - A mensagem deverá notificar via email os administradores do site

RF2 - Exibir ao visitante informações de contato

RF3 - Exibir ao visitante as vendas mais recentes

RF4 - Exibir ao visitante quantos serviços estão em progresso no momento

RF5 - Exibir número de acessos ao vivo

- CADASTRO

RF1 - Requisitar ao usuário um nome completo

RF2 - Requisitar ao usuário sua idade

RF3 - Requisitar ao usuário seu email

RF4 - Possibilitar ao usuário inserir seu CPF

RF5 - Para exercer as funções de um usuário verificado, exigir a confirmação do email via verificação

- PÁGINA DE ADMINISTRAÇÃO

RF1 - Exigir autenticação do usuário para acessar a página

RF2 - Exibir todas as reclamações em aberto a partir de clientes

RF3 - Exibir todas as reclamações em aberto a partir de vendedores

RF4 - Exibir relatório de vendas diárias, semanais e mensais

RF5 - Exibir todos os moderadores online no momento

## TIPOS DE USUÁRIO

- USUÁRIO NÃO VERIFICADO

RF1 - Restringir quaisquer alterações de dados de cadastro até que o usuário confirme o email

RF1.1 - Permitir ao usuário trocar o email de verificação da conta

RF2 - O usuário não verificado pode interagir somente como cliente

- USUÁRIO VERIFICADO

RF1 - Permitir que o usuário cadastrado altere sua foto de perfil

RF2 - Permitir que o usuário cadastrado altere seu nome de exibição

RF3 - Restringir do usuário a alteração de quaisquer outros dados de cadastro, apenas via suporte

RF4 - Permitir que o usuário cadastrado delete sua conta

RF5 - O usuário verificado com CPF cadastrado pode interagir como vendedor na página de contas

- MODERADOR

RF1 - A permissão de moderador só pode ser concedida pela administração do site

RF2 - O moderador pode visualizar a área de reclamações em aberto

RF3 - O moderador pode visualizar a área de reclamações em andamento

RF4 - O moderador pode alterar informações de cadastro de usuários comuns

## INTERAÇÕES COM VENDAS E AQUISIÇÕES DE CONTAS

- ANÚNCIO

RF1 - Exigir que o usuário esteja logado com uma conta verificada e com CPF para exercer as funções de anunciante

RF2 - Permitir ao anunciante divulgar uma conta

RF3 - Exigir que anuncio tenha título

RF3.1 - O título deve ter mais de 10 caracteres

RF4 - Exigir que o anúncio tenha descrição

RF4.1 - A descrição deve ter mais de 20 caracteres

RF4.2 - A descrição deve suportar markdown

RF5 - Exigir que o anúncio tenha uma imagem de capa

RF6 - Permitir que o anúncio possua imagens extras

RF7 - Exigir que o anúncio possua um preço em BRL

RF7.1 - O valor do preço não pode conter decimais

- AQUISIÇÃO

RF1 - Exigir que o usuário esteja logado com uma conta, não necessariamente verificada

RF2 - A aquisição de cada conta deve ser feita uma a uma, sem sistema de carrinho

RF3 - Permitir que o usuário realize o pagamento via pix ou cartão de crédito/débito

RF4 - Após confirmar a transação, abrir um chat para que cliente e anunciante se comuniquem e realizem a troca de informações sobre o envio do produto

RF5 - Permitir que o usuário cliente abra uma reclamação solicitando intervenção a administração

RF5.1 - O dinheiro da transação deve ser mantido em carteira durante 15 dias

RF5.1 - As reclamações deverão notificar a administração via email

RF5.2 - Ao abrir uma reclamação, o saldo do vendedor não pode ser sacado temporariamente

RF6 - O comprador pode marcar o produto como recebido

RF6.1 - O vendedor pode marcar o produto como entregue

# Regras de negócio - Requisitos não funcionais RNF

RNF1 - Navegador: O sistema deverá ser compatível com o Google Chrome, Microsoft Edge, Opera e Firefox.

RNF2 - Disponibilidade: O sistema deverá estar disponível 24 horas por dia, 7 dias por semana.

RNF3 - Segurança: O sistema deverá ser seguro, evitando que dados sensíveis dos clientes sejam expostos a terceiros.

RNF4 - Responsividade: O sistema deverá ser responsivo, permitindo que os clientes acessem a loja online de qualquer dispositivo, como computadores, tablets e smartphones.

RNF5 - Desempenho: O software deve ser capaz de processar um número considerado de acessos simultaneamente sem diminuir significativamente o desempenho.

RNF6 - Manutenção: O software deve ser facilmente mantido e atualizado, permitindo que os desenvolvedores adicionem novos recursos sem interromper o funcionamento do site.

# Diagrama de casos de uso

![Imagem](docs/Casos%20de%20uso.png "Casos de uso")
