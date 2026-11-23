<p align="center"><a href="../README.md"> Início</a> &nbsp;›&nbsp; <b>Etapa 2 · Ideação</b> &nbsp;›&nbsp; Diagramas MoLIC</p>

<p align="center"><img src="../assets/banner-molic.svg" alt="Banner — Diagramas MoLIC" width="100%"></p>

---

# 5. Diagramas MoLIC

## 5.1. Introdução

MoLIC é uma linguagem que os designers de IHC podem utilizar para modelar a interação dos usuários com sistemas computacionais, seguindo a metáfora de interação como conversa. Modelar a interação na MoLIC é modelar a conversa entre o usuário e o preposto (porta-voz) do designer cristalizado na interface.


## 5.2. Metodologia de construção

A elaboração dos diagramas MoLIC foi realizada com base nas HTAs e nos mapas de objetivos dos usuários, que serviram como referência para compreender melhor as necessidades, os objetivos e as atividades que cada perfil de usuário pretende realizar dentro do Camp Food. A partir dessas informações, foi possível organizar e representar os caminhos de interação entre os usuários e o sistema, considerando as diferentes ações e possibilidades de navegação na plataforma.

Para a construção e organização visual dos diagramas, foi utilizada a ferramenta draw.io, que permitiu estruturar as interações de maneira clara e facilitar a visualização das conversas entre os usuários e o sistema.




---
## 5.3. Diagramas MoLIC desenvolvidos

### 5.3.1. MoLIC de visão geral

Este diagrama apresenta o fluxo geral de interação do Camp Food, contemplando as principais ações que podem ser realizadas pelos usuários dentro da plataforma. O fluxo começa com o acesso ao sistema, no qual o usuário pode informar seus dados de login ou realizar um cadastro. Caso as informações sejam inválidas, o sistema apresenta uma indicação de erro, permitindo que o usuário tente novamente. Quando o acesso é validado, ele é direcionado ao catálogo de produtos e vendedores.

A cena Catálogo e vendedores funciona como um ponto central de navegação, pois reúne as informações disponíveis na plataforma, como produtos, preços, disponibilidade e vendedores cadastrados. A partir dela, o fluxo pode seguir por diferentes caminhos, de acordo com a ação que o usuário deseja realizar.
No caminho relacionado ao perfil da vendedora, o usuário pode acessar a cena Gestão de vendas, que reúne as opções de gerenciamento de produtos, estoque e solicitações recebidas. Nessa etapa, a vendedora pode atualizar as informações do estoque ou confirmar um pedido. Após realizar uma dessas ações, os dados são processados e o sistema apresenta a cena Atualização confirmada, exibindo uma mensagem para informar que a operação foi concluída. Em seguida, a vendedora pode encerrar essa interação.

Já no fluxo relacionado à compra, o usuário parte do catálogo para consultar um produto ou vendedor específico. Essa ação leva à cena Detalhes e compra, na qual são apresentadas informações como descrição, preço e localização, além da possibilidade de utilizar o chat e confirmar o pedido. Caso decida prosseguir com a compra, o sistema registra o pedido e direciona o usuário para a cena Pedido confirmado, que apresenta uma mensagem de confirmação e um resumo da solicitação realizada. Depois disso, o usuário pode sair e finalizar o fluxo.

O diagrama também considera a possibilidade de o usuário desistir da compra ou retornar à etapa anterior. Essa transição permite que ele volte ao catálogo sem precisar reiniciar todo o processo de acesso, podendo consultar outros produtos ou vendedores antes de tomar uma decisão.


<img width="900" alt="image" src="https://github.com/user-attachments/assets/33f582b4-b1f1-4631-aa9a-176b8dffec65" />

<p align="center"><sub><b>Figura 1.</b> MoLIC geral.</sub></p>





### 5.3.2. MoLIC : Acesso e autenticação

O fluxo começa quando o usuário inicia o acesso ao sistema. Nessa primeira cena, ele encontra as opções de login e cadastro, podendo informar seu login e senha caso já possua uma conta ou escolher a opção de cadastro para criar um novo acesso. Essa etapa é importante porque permite que o usuário entre na plataforma e tenha acesso às funcionalidades disponíveis. A transição acontece quando o usuário realiza a ação de autenticar ou cadastrar seus dados. Essas informações são encaminhadas para o sistema, que fica responsável por verificar se os dados informados são válidos.

Após a tentativa de acesso, o sistema realiza a validação das informações fornecidas pelo usuário. Esse momento é representado pelo quadrado preto no diagrama, indicando uma etapa de processamento do sistema, na qual os dados são verificados antes de permitir a continuidade da interação. Existem dois possíveis caminhos a partir dessa etapa. Caso os dados sejam inválidos, o sistema retorna o fluxo para a cena de acesso, permitindo que o usuário tente novamente, corrija as informações ou realize o cadastro. Dessa forma, o usuário não consegue avançar enquanto o acesso não for validado. Por outro lado, quando os dados são reconhecidos como válidos, o sistema permite que o usuário continue para a próxima cena.

Depois que o acesso é validado, o usuário é direcionado para o catálogo de vendedores. Nessa cena, ele pode visualizar a lista de vendedores disponíveis na plataforma, além de consultar informações sobre os produtos oferecidos, seus respectivos preços e a disponibilidade. Essa etapa representa o início da utilização das principais funcionalidades do CAMP FOOD, pois permite que o usuário conheça as opções de alimentação disponíveis e comece a procurar aquilo que deseja comprar.

De modo geral, esse fluxo organiza as primeiras etapas de utilização do CAMP FOOD, garantindo que o usuário passe pela autenticação antes de acessar o catálogo de vendedores. A possibilidade de retornar à tela de acesso quando os dados são inválidos também evita que o usuário avance sem uma autenticação válida. Assim, o diagrama apresenta o caminho inicial que conecta o acesso à plataforma com a consulta aos produtos e vendedores disponíveis.



<img width="736" height="414" alt="#banner #discord #ayaoosawa" src="https://github.com/user-attachments/assets/f62153b1-7709-4aff-9d76-b5e452304d0c" />

<p align="center"><sub><b>Figura 2.</b> MoLIC: Acesso e autenticação.</sub></p>




### 5.3.3. MoLIC : Fluxo da Vendedora


O fluxo inicia na cena do catálogo de vendedores, que apresenta a lista de vendedores disponíveis na plataforma, juntamente com seus produtos, preços e disponibilidade. A partir dessa tela, a vendedora pode iniciar o gerenciamento de seus produtos e pedidos, selecionando a opção correspondente. Essa ação representa a transição para a área de gerenciamento, permitindo que a vendedora tenha acesso às ferramentas necessárias para administrar suas vendas dentro da plataforma.

Após a solicitação de gerenciamento, o sistema realiza o processamento da ação e apresenta o painel de gestão de vendas. Essa etapa é representada pelo quadrado preto no diagrama e indica uma resposta do sistema à solicitação feita pela vendedora. Nessa cena, a vendedora tem acesso ao painel de gerenciamento, onde pode visualizar e administrar informações relacionadas aos produtos, ao estoque e às solicitações recebidas. Esse espaço permite que ela acompanhe suas vendas e realize as alterações necessárias para manter as informações da loja atualizadas.

A partir dessa tela, a vendedora pode realizar duas ações relacionadas: atualizar o estoque dos produtos e confirmar um pedido. Essas ações dão continuidade ao fluxo de interação e permitem que as informações sejam encaminhadas para processamento pelo sistema.

Depois que a vendedora realiza a atualização do estoque e confirma o pedido, o sistema processa essas informações para registrar as alterações realizadas. Essa etapa é representada por outro quadrado preto no diagrama. Quando o processamento é concluído, o sistema envia uma resposta indicando que os dados foram atualizados. Essa resposta permite que a interação avance para a próxima cena.

Após o processamento das informações, a vendedora é direcionada para a cena de atualização confirmada, na qual o sistema apresenta uma mensagem informando que as alterações foram realizadas com sucesso.Essa etapa é importante porque fornece um retorno à vendedora, permitindo que ela saiba que a atualização do estoque e a confirmação do pedido foram registradas pelo sistema. Por fim, a vendedora realiza a ação de encerrar a interação. Essa transição leva ao estado final do diagrama. 

De maneira geral, esse fluxo permite que a vendedora tenha controle sobre suas atividades dentro do CAMP FOOD, facilitando o gerenciamento dos produtos, do estoque e dos pedidos recebidos. Além disso, a mensagem de confirmação serve como um retorno do sistema, garantindo que a vendedora tenha conhecimento de que as alterações solicitadas foram processadas.



imagemmmmmm
<p align="center"><sub><b>Figura 3.</b> MoLIC: Fluxo da vendedora - Gestão de Vendas.</sub></p>



### 5.3.4. MoLIC : Fluxo do Comprador


O fluxo começa na cena do catálogo de vendedores, onde o usuário pode visualizar a lista de vendedores disponíveis na plataforma, além de consultar os produtos, preços e sua disponibilidade. A partir dessas informações, o comprador pode escolher um produto e consultar mais detalhes sobre ele e sobre o vendedor responsável pela venda. Essa funciona como o ponto inicial da busca do usuário, permitindo que ele conheça as opções disponíveis antes de decidir o que deseja comprar. Após o usuário selecionar a opção de consultar um produto e vendedor, o sistema realiza o processamento dessa solicitação. Essa etapa tem como função apresentar as informações solicitadas, encaminhando o usuário para a próxima cena.

Nessa cena, o comprador tem acesso a informações mais específicas sobre o produto e o vendedor, como descrição, preço, localização e chat. Também é apresentada a opção de confirmar o pedido, permitindo que o usuário dê continuidade à compra. Essa etapa oferece ao comprador as informações necessárias para avaliar o produto antes de realizar o pedido. Caso decida continuar, ele pode selecionar a opção de confirmação da compra. Além disso, o diagrama apresenta uma alternativa para essa cena: o usuário pode desistir ou voltar ao catálogo. Dessa forma, o comprador pode continuar procurando outros produtos ou vendedores sem precisar concluir a compra atual.

Quando o comprador decide confirmar a compra, o sistema recebe essa solicitação e realiza o processamento do pedido. Após o processamento, o sistema registra o pedido e encaminha o usuário para a cena de confirmação. Essa transição representa a resposta do sistema à ação realizada pelo comprador, indicando que a solicitação foi registrada.

Depois que o pedido é registrado, o comprador é direcionado para a cena de pedido confirmado. Nessa etapa, o sistema apresenta uma mensagem de confirmação acompanhada de um resumo do pedido, permitindo que o usuário tenha um retorno sobre a compra realizada.  Por fim, o usuário pode selecionar a opção de sair, encerrando o fluxo de interação. 

esse fluxo permite que o comprador utilize o CAMP FOOD para pesquisar vendedores, consultar produtos e realizar pedidos de forma organizada. A possibilidade de visualizar os detalhes antes da compra ajuda na tomada de decisão, enquanto a opção de desistir ou voltar ao catálogo oferece mais liberdade durante a navegação. Por fim, a confirmação do pedido fornece um retorno ao usuário sobre a conclusão da solicitação.


imagemmmm
<p align="center"><sub><b>Figura 4.</b> MoLIC: Fluxo do Comprador - Consultar a compra.</sub></p>



<p align="center">⬅️ <a href="4-htas.md">HTAs</a> &nbsp;·&nbsp; <a href="../README.md"> Voltar ao início</a> &nbsp;·&nbsp; <a href="../03-prototipacao/1-sketches.md">Sketches</a> ➡️</p>
