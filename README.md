# ☕ Café Aroma 

— Sistema de Gestão de Mesas

Sistema de PDV (Ponto de Venda) para gerenciamento de mesas de cafeteria, desenvolvido com HTML, CSS e JavaScript puro — sem frameworks ou dependências externas.

📸 Preview

Interface baseada no sistema real do Café Aroma, com mapa de mesas, lista de pedidos e gestão de atendentes.


🗂️ Estrutura do Projeto
cafe-aroma/
├── index.html   → Estrutura HTML da aplicação
├── style.css    → Estilos e layout visual
├── data.js      → Dados das mesas e catálogo de produtos
├── app.js       → Lógica da aplicação (renderização, eventos)
├── logo.jpeg    → Logo do Café Aroma
└── README.md    → Este arquivo

✨ Funcionalidades

Mapa de Mesas com 20 mesas e 3 status visuais:

🟤 Ocupada — mesa com pedido em andamento
🟦 Livre — mesa disponível
🟠 Parcial — mesa com consumo iniciado


Filtros por status de mesa e por atendente
Painel de pedidos com lista de itens, subtotal e total
Modal de Produtos — adiciona itens ao pedido da mesa selecionada
Modal de Funções — cancelar pedido, transferir mesa, aplicar desconto, fechar conta
Campo de observação por pedido
Toast de feedback para todas as ações
