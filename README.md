# Projeto Integrador - Modelo

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

- [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
- [Backend](github.com/marcoandre/pi-backend)
- [Frontend](github.com/marcoandre/pi-frontend)

# Como usar esse modelo para o Projeto Integrador

1. Faça um fork desse repositório para a sua conta do GitHub.
2. Clone o repositório para o seu computador.
3. Abra o arquivo README.md no seu editor de texto favorito (recomendamos o [Visual Studio Code](https://code.visualstudio.com/)).
4. Tenha instalada a extensão [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) no seu editor de texto.
5. Edite o arquivo README.md com as informações do seu projeto.

# Desenvolvimento

- As equipes serão avaliadas por cada etapa da documentação e entregas realizadas.
- Cada equipe deverá escolher um sistema para o desenvolvimento das atividades, a partir dos modelos apresentados.

# Modelos de Sistemas

**Nessa parte a equipe deve escolher um dos modelos de sistemas para desenvolver o projeto. Ao escolher, escreva uma breve descrição do sistema e o motivo da escolha e pode apagar os outros modelos.**

## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma padaria**

O nosso cliente, Sr. Genival, tem uma padaria de bairro chamada padaria Pão Genial e, devido a qualidade de seus produtos, ela está crescendo rapidamente. Recentemente, ele contratou mais funcionários para atendimento, caixa, panificação, etc.
Assim, atualmente, ele consegue concentrar seus esforços para melhorar a gestão da padaria. Para isso, ele quer instalar um sistema de controle de vendas que permita ao caixa lançar as vendas realizadas. Como sua intenção
é melhorar a gestão do negócio, é muito importante que ele consiga ter
relatórios, como por exemplo, de vendas.

## 2- Empréstimo

**Gerenciamento de uma biblioteca**

Uma ONG, chamada Sala Arco Íris, ajuda crianças de baixa renda em sua educação básica. Atualmente, recebeu uma doação de mais de 1000 livros e está montando a sua biblioteca. Eles querem emprestar os livros para as crianças e os pais das crianças. Apesar de
terem um computador e as estantes necessárias à disposição nessa nova biblioteca, não possuem verba suficiente para um leitor de impressão digital ou para produção
de carteirinhas para todas as crianças. Para isso, eles precisam de um sistema que gerencie todo o acervo, empréstimos, livros disponíveis, etc. mas que isso ocorra de maneira simples e sem necessidade de novos gastos. Também é importante que haja relatórios, permitindo o controle dos empréstimos e dos livros disponíveis no acervo.

## 3- Ordem de Serviço (O.S.)

**Manutenção de computadores**

Sr. Sálvio, nosso cliente, fez um curso de manutenção de celulares e smartphones e decidiu abrir um negócio, onde ele é responsável pelos consertos e sua esposa Marília realiza os atendimentos aos clientes. Com sua visão empreendedora, ele sentiu a necessidade de um software que auxilie
sua esposa nas tarefas diárias. Para isso, ele deseja um sistema que gerencie os clientes, orçamentos, serviços e retirada dos equipamentos. Sendo um negócio pequeno, é muito importante que ele consiga ter relatórios que lhe ajudem na gestão da
empresa, como dos status dos serviços.

# Situação Problema

**Nessa parte a equipe deve descrever a situação problema que será resolvida pelo sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.**

![Ciclo da Venda](docs/ciclo_da_venda.webp "Ciclo da Venda")

Descrevem o que acontece atualmente na empresa em um contexto global,
abordando o funcionamento da empresa como um todo, não apenas os “problemas” que lá ocorrem.

Sabendo disso, seu papel é **detalhar o funcionamento da empresa escolhida na
atualidade, ou seja, antes de seu novo software**, usando como base a situação que passamos, mas aprofundando os detalhes de como as coisas acontecem.

- Pesquise sobre empresas do ramo escolhido
  para entender como funcionam;
- Aproveite seus conhecimentos previamente adquiridos na área da empresa que escolheu, se houver;
- Simule uma situação real. Lembre-se que são
  propostas com empresas fictícias, sendo assim,
  você terá que tomar certas decisões sobre como
  a empresa funciona em relação às coisas que
  não estão definidas no documento base (por
  exemplo, no caso da padaria, dizemos que seu
  Genival contratou mais funcionários, mas saber
  quantos e o que fazem pode ser relevante para o software), então tente “visualizar” a
  empresa funcionando, como se você estivesse lá acompanhando o dia-a-dia;

Seguindo essas dicas, você deve ser capaz de descrever o dia-a-dia da empresa selecionada. E para ajudar na organização do texto, indicamos uma abordagem em 3 etapas:

- **Introdução**: A equipe Wolf E-Sports sente a necessidade de um software que possibilite a contratação de serviços remotos e a gerência dos mesmos, tendo em vista que realiza toda a logística de forma manual atualmente, necessita de um software completo que providencie um sistema de pagamento online prático e eficiente, facilitando o contato entre o prestador de serviço e o contratante para que o serviço comece o quanto antes, dando suporte para todas as modalidades de venda que a equipe pratica.
- **Situação-problema**: Com a alta dos jogos online, muitos jogadores sentem a necessidade de estar ranqueado entre os melhores, seja para jogar com pessoas de alto nível ou por simples status. Porém nem sempre é possível alcançar tal ranque por conta própria, por falta de tempo/treino ou coisas do gênero. Então a equipe Wolf E-Sports, que possui muitos jogadores habilidosos, oferece uma espécie de alavancamento no ranque para aqueles que desejam contratar o serviço. O serviço geralmente consiste em o contratante enviar as informações da sua conta no jogo para o prestador de serviço, que por sua vez vai vencer nela uma quantidade de partidas conforme o que foi contratado, o custo varia de acordo com o quão longe o contratante deseja ir, sendo mais barato nos ranques mais baixos e encarecendo linearmente.
- A Wolf E-Sports também trabalha com venda de contas neste mesmo jogo, variando o preço de acordo com três métricas principais: nível, quantidade de conteúdo adquirido na mesma e ranque.

- **Conclusão**: As principais dificuldades da equipe atualmente são: a baixa confiabilidade da entrega do serviço já que o pagamento é feito de forma manual, necessitando de um software mais prático com pix integrado, e também a logística pouco eficiente que é utilizada atualmente onde o contratante entra em contato com o dono que precisa contactar cada um de seus jogadores para confirmar se há disponibilidade para atender aquele serviço, assim como o repasse do pagamento, e também seria útil um meio de contato entre cliente e prestador de serviço, ou algo do gênero para um acompanhamento em tempo real do progresso do serviço contratado.

# Descrição da proposta

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

Tenha em mente que essa é uma etapa relativamente breve. Não é necessário um texto gigantesco, apenas dar uma noção do funcionamento do sistema. Mais adiante
precisaremos ser bem detalhistas, todavia agora a intenção é apenas fazer algo que permita ao cliente nos dizer se estamos no caminho certo.

# Regras de negócio - Requisitos funcionais RF

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
