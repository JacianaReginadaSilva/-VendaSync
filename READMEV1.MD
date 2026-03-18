VendaSync - Sistema de Gestão de 
Vendas (Parte 1) 
Este projeto é o estágio inicial de um sistema de gestão voltado para pequenos 
comerciantes, focado em agilizar o registro de pedidos e a validação de endereços 
de entrega. 
�
� Estrutura do Projeto 
O projeto foi desenvolvido em uma estrutura de arquivo único para facilitar a 
portabilidade e visualização imediata: 
• HTML5: Estrutura semântica dos componentes. 
• Tailwind CSS: Framework utilitário para design moderno e responsivo. 
• JavaScript (Vanilla): Lógica de manipulação do DOM, cálculos e consumo 
de API. 
�
� Como Rodar o Sistema 
1. Certifique-se de ter um navegador moderno instalado (Chrome, Edge ou 
Firefox). 
2. Salve o código fornecido no arquivo vendas_app.html. 
3. Abra o arquivo diretamente no seu navegador clicando duas vezes sobre ele. 
4. Para a integração do CEP funcionar, é necessária uma conexão ativa com a 
internet. 
✨ Funcionalidades Implementadas 
1. Catálogo de Produtos: Armazenado em um array de objetos JavaScript, 
exibido dinamicamente na interface com nome, preço e categoria. 
2. Calculadora de Descontos: Permite selecionar um produto e aplicar uma 
porcentagem de desconto em tempo real, calculando o valor final 
instantaneamente. 
3. Consumo de API (Brasil API): Integração assíncrona que busca logradouro, 
cidade e estado a partir do CEP inserido pelo usuário. 
4. Interface Responsiva: Design limpo e adaptável para diferentes tamanhos 
de tela usando Tailwind CSS.