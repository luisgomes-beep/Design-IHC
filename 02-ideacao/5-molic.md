<p align="center"><a href="../README.md"> Início</a> &nbsp;›&nbsp; <b>Etapa 2 · Ideação</b> &nbsp;›&nbsp; Diagramas MoLIC</p>

<p align="center"><img src="../assets/banner-molic.svg" alt="Banner — Diagramas MoLIC" width="100%"></p>

---

# 5. Diagramas MoLIC

## 5.1. Introdução

MoLIC é uma linguagem que os designers de IHC podem utilizar para modelar a interação dos usuários com sistemas computacionais, seguindo a metáfora de interação como conversa. Modelar a interação na MoLIC é modelar a conversa entre o usuário e o preposto (porta-voz) do designer cristalizado na interface.

---

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




![Diagrama MoLIC: visão geral](./Molic%20visão%20geral.drawio.png)



<p align="center">⬅️ <a href="4-htas.md">HTAs</a> &nbsp;·&nbsp; <a href="../README.md"> Voltar ao início</a> &nbsp;·&nbsp; <a href="../03-prototipacao/1-sketches.md">Sketches</a> ➡️</p>
