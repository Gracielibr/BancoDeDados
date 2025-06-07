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
<img align="right" height="80" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Microsoft_Azure.svg/1200px-Microsoft_Azure.svg.png">
Se queremos gerenciar nossos dados usando a nuvem, podemos apenas usar máquinas virtuais do Azure para hospedar nossas próprias instâncias do Microsoft SQL Server. Às vezes essa é a solução certa, mas o Azure oferece outra maneira que costuma ser muito mais fácil e econômica. Os bancos de dados SQL do Azure são uma oferta de PaaS (plataforma como serviço). Isso significa gerenciar muito menos infraestruturas e manutenções.

Conveniência

Configurar o SQL Server em uma máquina virtual (VM) ou em hardware físico requer que você conheça os requisitos de hardware e software. Você precisa entender as melhores práticas de segurança mais recentes e gerenciar o sistema operacional e os patches do SQL Server de forma rotineira. Você também precisa gerenciar questões backup e retenção de dados por conta própria.

Com o Banco de Dados SQL do Azure, podemos gerenciar o hardware, as atualizações de software e os patches do sistema operacional para você. Tudo o que você especifica é o nome do banco de dados e algumas opções, e você tem um banco de dados SQL em execução em minutos.

Você pode ativar e destruir instâncias de Banco de Dados SQL do Azure como quiser. O Banco de Dados SQL do Azure é ativado rapidamente e é fácil de configurar. Você pode concentrar-se menos em configurar o software e mais em criar um ótimo aplicativo.

Custo

Uma vez que nós realizamos o gerenciamento, você não precisa comprar, alimentar nem realizar a manutenção de nenhum sistema.

O Banco de Dados SQL do Azure tem várias opções de preços. Essas opções de preço permitem equilibrar o desempenho e o custo, com um custo previsível. Você pode começar com apenas alguns dólares por mês.

Escala

Você descobre que a quantidade de dados de logística de transporte que você precisa armazenar dobra a cada ano. Quando você opera no local, quanta capacidade excedente você deve planejar?

Com o Banco de Dados SQL do Azure, você poderá ajustar o desempenho e o tamanho do banco de dados imediatamente quando suas necessidades mudarem.

Segurança

O Banco de Dados SQL do Azure vem com um firewall configurado por padrão para bloquear conexões da Internet pública. Você controla o acesso aos seus dados.

Você pode permitir o acesso de endereços IP específicos nos quais você confia. Fazendo isso, você pode usar o Visual Studio, o SQL Server Management Studio ou outras ferramentas para gerenciar seu Banco de Dados SQL do Azure.




<div align="center">
  <p><strong>Captura de tela do Azure</strong></p>
  <img src="https://github.com/user-attachments/assets/8a5079d0-9296-4e24-8dd6-0ae95dc61c54" 
       alt="Captura de tela do Azure" 
       width="600" 
       height="450">
</div>

Criar Servidor do Banco de Dados SQL. para cria um novo quando aparecer servido, abaixo tera novo servido clicando nele redirecionado a oura janela, na qual vc dara o neme e comora a regiao que pretende usar confor a inagem a baixo, escola a forma de autenticao e a pagina será redinecionada para a jaanela anterior para conculir o processo .



Imagem 4 
Enquanto a implantação está em andamento, os detalhes da implantação exibem os recursos que são criados. Quando a implantação for concluída, opcionalmente, selecione Fixar no painel e depois clique em Acessar o recurso. O painel Visão geral do servidor do banco de dados SQL é exibido. Agora, seu banco de dados SQL do Azure está em funcionamento.


ja criado 
imagem 2
selecionar A opção Definir firewall do servidor é exibida na página Visão geral do banco de dados. No SQL Server lógico do Azure, selecione Rede em Segurança no menu de serviço.
