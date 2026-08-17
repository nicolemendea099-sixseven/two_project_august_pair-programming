# two_project_august_pair-programming
🥖 PADARIA ARTES - SISTEMA DE VENDAS

Este projeto é um sistema de vendas para a Padaria Artes, desenvolvido em Python com uma interface gráfica criada utilizando Tkinter.

O sistema permite visualizar o cardápio, selecionar produtos, controlar o estoque, cadastrar clientes, registrar pagamentos, gerar pedidos e recibos e consultar informações das vendas.

🎯 OBJETIVOS DO PROJETO
Criar um sistema de vendas para uma padaria.
Desenvolver uma interface gráfica utilizando Tkinter.
Organizar os produtos por categorias.
Controlar o estoque dos produtos.
Cadastrar e consultar clientes.
Registrar vendas e formas de pagamento.
Gerar pedidos em formato JSON.
Gerar recibos em formato TXT.
Armazenar informações do sistema em arquivos JSON.
🚀 FUNCIONALIDADES
🛒 SISTEMA DE VENDAS

O sistema permite:

Visualizar os produtos disponíveis.
Selecionar a quantidade de cada produto.
Calcular automaticamente o total da compra.
Limpar as quantidades selecionadas.
Finalizar pedidos.
Registrar as informações da venda.
🍞 CARDÁPIO

Os produtos são organizados em categorias:

🍞 Pães
🥐 Salgados
🍰 Bolos e tortas
🍮 Doces
☕ Bebidas

Cada produto possui informações como:

Nome
Descrição
Preço
Estoque
Identificação
📦 CONTROLE DE ESTOQUE

O sistema realiza o controle do estoque dos produtos.

Funcionalidades:

Visualização da quantidade disponível.
Identificação de produtos esgotados.
Limitação da quantidade que pode ser comprada.
Atualização automática do estoque após uma venda.
Armazenamento do estoque em arquivo JSON.

Os dados são armazenados em:

dados/estoque.json
👥 CADASTRO DE CLIENTES

O sistema permite registrar informações dos clientes, como:

Nome
Telefone
Quantidade de pedidos
Total gasto

Também é possível consultar os clientes cadastrados através da interface.

Os dados são armazenados em:

dados/clientes.json

💳 FORMAS DE PAGAMENTO

O sistema possui as seguintes formas de pagamento:

💵 Dinheiro
💳 Débito
💳 Crédito
📱 Pix

No pagamento em dinheiro, o sistema calcula automaticamente o troco.

Caso o valor recebido seja menor que o valor da compra, o pagamento não pode ser confirmado.

🧾 RECIBOS

Depois da finalização de uma venda, o sistema gera um recibo com informações como:

Nome da padaria
Data e horário
Cliente
Produtos
Quantidades
Valores
Total da compra
Forma de pagamento
Valor recebido
Troco

O recibo pode ser visualizado na aplicação e também salvo em formato .txt.

📊 RELATÓRIO DE VENDAS

O sistema mantém informações sobre as vendas realizadas.

O relatório apresenta:

Quantidade de pedidos
Quantidade de produtos vendidos
Faturamento
Produto mais vendido

As informações são armazenadas em:

dados/relatorio.json

🌙 MODO CLARO E ESCURO

A interface possui dois temas:

☀️ Modo Claro
🌙 Modo Escuro

O usuário pode alternar entre os temas através do botão disponível na interface.

🖥️ INTERFACE GRÁFICA

A interface foi desenvolvida utilizando:

tkinter
ttk

O sistema possui:

Abas para as categorias
Cartões de produtos
Botões de ação
Campos de entrada
Seletores de quantidade
Tela de pagamento
Tela de recibo
Tela de clientes
Tela de relatório
Modo claro e escuro
🛠️ TECNOLOGIAS UTILIZADAS
🐍 Python
🖼️ Tkinter
🎨 ttk
📄 JSON
📁 OS
🕐 Datetime

O projeto utiliza apenas recursos da biblioteca padrão do Python, não sendo necessário instalar bibliotecas externas.

📋 PRÉ-REQUISITOS

Para executar o sistema, é necessário ter:

Python 3 instalado.
Tkinter disponível na instalação do Python.
Windows, Linux ou macOS.
▶️ COMO EXECUTAR

Primeiro, renomeie o arquivo do código para:

padaria_artes.py

Depois, abra o terminal dentro da pasta do projeto e execute:

python padaria_artes.py

A interface da Padaria Artes será aberta automaticamente.

📁 ESTRUTURA DO PROJETO

A estrutura do projeto pode ficar assim:

Padaria-Artes/
│
├── padaria_artes.py
│
├── dados/
│   ├── estoque.json
│   ├── clientes.json
│   └── relatorio.json
│
├── ticket/
│   ├── pedido_YYYYMMDD_HHMMSS.json
│   └── pedido_YYYYMMDD_HHMMSS_recibo.txt
│
└── README.md

A pasta dados armazena as informações de estoque, clientes e relatórios.

A pasta ticket armazena os pedidos e recibos gerados pelo sistema.

💰 FUNCIONAMENTO DE UMA VENDA

O processo de venda funciona da seguinte forma:

Selecionar os produtos.
Escolher as quantidades.
Conferir o total da compra.
Iniciar o processo de pagamento.
Informar os dados do cliente.
Escolher a forma de pagamento.
Confirmar o pagamento.
Atualizar o estoque.
Registrar a venda.
Gerar o pedido em JSON.
Gerar o recibo em TXT.
📄 ARQUIVOS GERADOS
📦 estoque.json

Armazena as quantidades disponíveis dos produtos.

👥 clientes.json

Armazena os dados dos clientes e suas informações de compras.

📊 relatorio.json

Armazena os dados das vendas realizadas.

🧾 Arquivos .json dos pedidos

Cada pedido pode ser armazenado individualmente com suas informações.

📄 Arquivos .txt

Contêm os recibos das compras realizadas.

📌 INFORMAÇÕES DO PROJETO

Nome: Padaria Artes
Linguagem: Python
Interface gráfica: Tkinter
Tipo: Sistema de vendas
Arquivo principal: padaria_artes.py
