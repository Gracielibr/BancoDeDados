# Banco De Dados
Desafio da DIO, para praticar o processo de configuração de uma instância de Banco de Dados na plataforma Microsoft Azure.
<img align="right" height="200" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4xRmJAr1RW2g9yaEJS-OMT09nVx53t-TKrw&s">

Como entregável, o desafio proposto é a criação de um repositório contendo resumos, anotações e dicas sobre o uso da Azure, servindo como material de apoio para estudos e futuras implementações.  resumos, anotações e dicas sobre o uso da Azure.

## O que é Banco de Dados?

Imagine um banco de dados como uma grande biblioteca digital, onde todas as informações são cuidadosamente organizadas para que você possa encontrar exatamente o que precisa em poucos segundos. Ele funciona como um armário bem arrumado, onde cada coisa tem seu lugar como textos, números, imagens, vídeos e qualquer outro tipo de dado, tudo sendo quardado em sua pasta específica, na qual são armazenados de forma lógica e estruturada, prontos para serem usados quando necessário. No dia a dia, os bancos de dados estão por trás de quase tudo o que fazemos online. Quando você entra em uma rede social, como o Instragran e o Facebook , é o banco de dados que guarda seu perfil, suas fotos e suas mensagens. Quando faz uma compra na internet, como nos sites Mercado Livre e Ifood, ele armazena os produtos, os pedidos e os dados de pagamento. Até mesmo os aplicativos de mensagem, como WhatsApp, dependem deles para manter o histórico das suas conversas.

Para gerenciar tudo isso, existe um software especial chamado Sistema de Gerenciamento de Banco de Dados (SGBD). Ele é como se fosse um bibliotecário ou o organizador desse armário digital, controlando quem pode acessar, alterar ou adicionar informações, garantindo que tudo funcione de maneira segura e eficiente.
Os bancos de dados podem ser divididos em dois grandes grupos, cada um com suas características e usos específicos. Os bancos de dados relacionais, também conhecidos como SQL, organizam as informações em tabelas, parecidas com planilhas do Excel, onde os dados se relacionam entre si. Por exemplo, uma tabela pode ter clientes e outra de pedidos, e é possível conectar as duas para saber quem comprou o quê.
Para trabalhar com esse tipo de banco, usa-se a linguagem SQL, que permite buscar, inserir, atualizar e apagar dados com comandos simples. Alguns exemplos populares são MySQL, PostgreSQL e Oracle.
Já os bancos de dados não relacionais, ou NoSQL, são mais flexíveis e não usam tabelas. Eles são ideais para guardar informações que não se encaixam bem em estruturas rígidas, como posts de redes sociais, dados de sensores inteligentes ou até mesmo os registros de um jogo online. Entre os mais conhecidos estão o MongoDB, que armazena dados em formato de documentos, o Redis, que trabalha com dados em memória para respostas ultrarrápidas, e o Neo4j, especializado em lidar com relações complexas, como as conexões entre pessoas em uma rede social.

Em um mundo cada vez mais digital, os bancos de dados são a base que sustenta praticamente todos os sistemas que que são usados. Eles garantem que as informações sejam armazenadas com segurança, organizadas de forma inteligente e recuperadas em um piscar de olhos quando presisar delas. 


## Crindo Danco de Dados SQL na Microsoft Azure

O Banco de Dados SQL do Azure se diferencia significativamente das soluções tradicionais de gerenciamento de dados por sua abordagem como serviço gerenciado na nuvem. Enquanto soluções convencionais exigem amplo conhecimento técnico para configuração e manutenção de infraestrutura, a versão Azure simplifica radicalmente esse processo. A principal diferença está na natureza PaaS (Plataforma como Serviço), que transfere para a Microsoft a responsabilidade pelo gerenciamento do hardware, atualizações de sistema e manutenção rotineira.

Diferentemente de implementações tradicionais onde é necessário planejar capacidade antecipadamente e lidar com upgrades complexos, o Banco de Dados SQL do Azure oferece escalabilidade instantânea para atender a demandas flutuantes. O modelo de custo também apresenta uma diferença marcante - em vez de investimentos iniciais em hardware, os usuários pagam apenas pelo que consomem, com opções que variam desde planos básicos até configurações de alto desempenho.

A segurança integrada representa outra distinção importante, com proteções como firewall nativo e controle granular de acesso já incorporados ao serviço, eliminando a necessidade de configurações manuais complexas. Essa abordagem permite que equipes de desenvolvimento dediquem mais tempo à criação de valor através de aplicativos, enquanto a plataforma cuida da camada de infraestrutura subjacente, adaptando-se automaticamente às necessidades em evolução de cada projeto.










<img align="right" height="80" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Microsoft_Azure.svg/1200px-Microsoft_Azure.svg.png">


Para criar um Banco de Dados SQL, após acessar a plataforma da  Microsoft Azure na página inicial, basta posicionar o cursor do mouse sobre o ícone do Banco ede Bados para que seja exibida uma janela com um tutorial explicativo, para que nuca realizou uma criação de banco de daods nesta plataforma, usar o tutorial é uma maeira muito pratica e criar, além de adiquerir conhecimento, pois ele denostra o passo-a-passo.Por isso para criar este basco de bados foi utilizado o os 

<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/8a5079d0-9296-4e24-8dd6-0ae95dc61c54" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>







<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/fbe67afb-8ab8-4138-afd7-a46613dcbf80" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>


<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/52ad87bb-1664-4d33-adf9-7cf3337831b2" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>
Criar Servidor do Banco de Dados SQL. para cria um novo quando aparecer servido, abaixo tera novo servido clicando nele redirecionado a oura janela, na qual vc dara o neme e comora a regiao que pretende usar confor a inagem a baixo, escola a forma de autenticao e a pagina será redinecionada para a jaanela anterior para conculir o processo .

<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/62caf2f5-f9b9-4a73-a141-be43060031d6" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>

<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/f148e95d-4844-4be2-8c8d-bd36d0244ab3" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>

Imagem 
Enquanto a implantação está em andamento, os detalhes da implantação exibem os recursos que são criados. Quando a implantação for concluída, opcionalmente, selecione Fixar no painel e depois clique em Acessar o recurso. O painel Visão geral do servidor do banco de dados SQL é exibido. Agora, seu banco de dados SQL do Azure está em funcionamento.
<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/4bc6d920-b807-47e3-9187-01f1f1694eb9" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>

<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/674f772c-7418-4187-a5ab-03d88590eecd" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>

<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/d3204f19-9120-4dae-a172-aa1504d0ec91" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>

ja criado 
imagem 2
selecionar A opção Definir firewall do servidor é exibida na página Visão geral do banco de dados. No SQL Server lógico do Azure, selecione Rede em Segurança no menu de serviço.

<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/c01df7b3-b4b5-4e5d-9237-3dcff245fc84" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>


<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/4fcae9c9-2bf2-4a80-859e-b265a43d7a7a" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>



