# Modelagem Ágil

<!-- 
**Foco_03:** Modelagem Ágil
Entrega Mínina: Backlog do Produto, Priorizado com MOSCOW, e com 3 Níveis de Granularidade (pelo menos).

Apresentação (em sala) explicando o Backlog do Produto, com: (i) rastro claro aos membros participantes; (ii) justificativas & senso crítico sobre esse artefato; (iii) breve apresentação do Backlog, priorizado, e com três a seis níveis de granularidade (entre: Theme, Epic, Feature, Story, Task, Acceptance Criterion), e (iv) comentários gerais sobre iniciativas extras. Tempo da Apresentação: +/- 5min. Recomendação: Apresentar diretamente via Wiki ou GitPages do Projeto.

A Wiki ou GitPages do Projeto deve conter um tópico dedicado ao Módulo Modelagem Ágil, com Backlog do Produto, histórico de versões, referências, vídeo de entrega, e demais detalhamentos gerados pela equipe nesse escopo.

Demais orientações disponíveis nas Diretrizes (vide Moodle).
-->

# 1. Product Backlog

## 1.1. Introdução

<p style="text-indent: 20px; text-align: justify">
O Product Backlog, um dos pilares do desenvolvimento Scrum, é uma lista contendo todas as funcionalidades desejadas para um produto. O conteúdo desta lista é definido pelo Product Owner, o responsável por gerenciar e definir esses itens. Ademais, o Product Backlog não precisa estar completo no início de um projeto, isto é, pode-se começar com tudo aquilo que é mais óbvio em um primeiro momento e com o tempo alterá-lo, a medida que se aprende mais sobre o produto e seus usuários.
</p>

## 1.2. Metodologia

<p style="text-indent: 20px; text-align: justify">
Para a criação do backlog todos os integrantes do grupo se reunirão e por meio de um brainstorm os requisitos foram elicitados e em seguida modelados. As tasks das USs foram definidas pelo Ailton Aires.
</p>

## 1.3. Product Backlog

<table>
    <thead>
        <tr style="background-color: #54CCFF">
            <th style="border-style:solid;border-width:1px;text-align:center">Tema</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Épico</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Feature</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Rastreabilidade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Tasks</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="100%">Bazar</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="4"> Gerenciamento de registro do cliente</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Registro do cliente</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> brainstorm e storyboard </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como cliente, eu gostaria de me cadastrar para que meus dados de compra fiquem salvos</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Estruturar o Banco de Dados</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, eu gostaria de cadastrar dados de pagamento para facilitar a compra online.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Cadastrar cartão, implementar tela de pagamento cadastro dos dados</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Edição de dados do usuário</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, eu gostaria de recuperar a minha senha para não perder minha conta.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar botão "esqueci minha senha", opcção para colocar email de segurança</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, eu gostaria de editar os meus dados da conta para que não ocorra problemas com informações desatualizadas</td>
             <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar botão para editar perfil, definir querys pra atualizar os dados no banco</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan = "3">Comunicação do cliente com a empresa</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan = "2">Suporte de Usuário</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, desejo ter acesso ao atendimento de usuário para conseguir informações sobre meu pedido</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar uma tela de SAC, disponibilizar canais de atendimento</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, desejo falar com os responsáveis pela venda para resolver eventuais problemas</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar e integrar chat entre vendedor e cliente</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Feedback do cliente</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, desejo avaliar a compra efetuada para dar meu feedback ao vendedor.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Colocar uma aba de avaliação do pedido, criar um sistema em estrelas da avaliação do pedido</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="13">Gerenciamento do pedido</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="9">Compra do produto</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> brainstorm e storyboard</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como cliente, eu gostaria de ver os produtos disponíveis para que eu possa escolher qual comprar</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Colocar um selo nos produtos disponíveis, filtrar os produtos por itens disponíveis</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US09</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> como cliente, eu gostaria de adicionar um produto ao meu carrinho para gerenciar a minha compra</td>
             <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar um carrinho de compras, permitir que remova o item do carrinho, permitir que mova para a lista de desejos</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US10</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">  Como cliente, gostaria de receber informações de entrega para que eu saiba em que trajeto meu produto se encontra</td>
             <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Integrar o app com um sistema de rastreio, disponibilizar o código de rastreio</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm e storyboard</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US11</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, gostaria de receber informações sobre a finalização do meu pedido. </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Enviar uma mensagem de confirmação de entrega do pedido</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US12</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, desejo ter acesso a informações sobre o processamento do pagamento</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar uma tela de detalhes do pagamento, enviar por email o status do pagamento</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US13</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como cliente, desejo poder visualizar os itens adicionados ao carrinho para confirmar meus pedidos antes de efetuar a compra.</td>
             <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar uma tela de confirmação do pedido, disponibilizar o valor total da compra</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US14</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como usuário, desejo remover um ou mais itens do carrinho para caso eu desista da compra destes itens.</td>
             <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar caixa de seleção de itens para serem removidos do carrinho </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
              <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Protótipo </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US27</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como cliente, gostaria de cadastrar um produto na minha lista de desejos para que eu salve os produtos que mais gostei</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Protótipo </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US28</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como cliente, gostaria de remover um produto na minha lista de desejos caso eu não tenha mais interesse no produto</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan = "4">Venda do produto</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US16</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como vendedor, desejo ter acesso ao pagamento referente ao meu produto vendido.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Disponibilizar tela de detalhes dos pagamentos para cada item vendido </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US17</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como vendedor, desejo visualizar a lista de produtos vendidos para fazer o encaminhamento para o cliente.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Disponibilizar tela da lista de itens vendidos </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US18</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como vendedor, gostaria de realizar uma ou mais vendas, para que os dados fiquem registrados no sistema. </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Permitir que os vendedores cadastrem um ou mais itens para venda </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" >brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US19</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">  Como vendedor, gostaria de poder gerar o recibo (nota fiscal) referente a venda, para poder fornecê-la ao cliente.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Implementar a geração da nota, permitir o download do arquivo </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2"> Gerenciamento do produto</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Cadastro de produto</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US20</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como vendedor, desejo realizar o cadastro de um produto para venda e disponibilizar na plataforma.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Permitir inserção de imagens do produto, título e descrição </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Edição do produto</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> brainstorm</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US21</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como vendedor, desejo tornar indisponível um produto cadastrado para quando não houver estoque.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Criar um botão pra remover o produto, criar uma query no banco de dados para remover/inativar a venda do produto </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
        </tr>
              <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2"> Gerenciamento de campanha</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Cadastro da campanha</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> StoryBoard </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US24</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como vendedor, gostaria de cadastrar uma campanha na plataforma</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Edição da campanha</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> StoryBoard </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US25</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> Como vendedor, gostaria de editar uma campanha na plataforma</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
    </tbody>
<table>

## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 15): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 46 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668185/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 08 mar. 2022.


## Histórico de versão
| Data | Versão | Autor | Descrição | Revisor |
| :-: | :-: | :-: | :-: | :-: |
| 26/06/2022 | 1.0 | Todos | Criação do artefato: Backlog | Todos |
| 15/07/2022 | 1.1 | [Ailton Aires](https://github.com/ailtonaires) | Criação das tasks para as USs | [Douglas Monteles](https://github.com/douglasmonteles) |
| 30/07/2022 | 2.0 | [Ailton Aires](https://github.com/ailtonaires) | Criação das tasks para as USs | [Gabriel](https://github.com/GabrielCostaDeOliveira) |
| 05/08/2022 | 3.0 | [Gabriel](https://github.com/GabrielCostaDeOliveira) [Ailton Aires](https://github.com/ailtonaires)  [Athur](https://github.com/art1505)| Adicionando rastreabilidades e novas US | |
| 08/08/2022 | 3.1 | [Gabriel](https://github.com/GabrielCostaDeOliveira) [Lais](https://github.com/laispa)  [Douglas Monteles](https://github.com/douglasmonteles) |Correção da rastreabilidade | |
| 11/08/2022 | 3.2 | [Gabriel](https://github.com/GabrielCostaDeOliveira) | Correção Estrutural| |
