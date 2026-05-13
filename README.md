# SQLWorkbench
Refinamento basico de Projeto conceitual de banco de dados de um e-commerce
Especialização de Clientes (PF/PJ): Implementei uma estrutura de "Super-entidade", onde a tabela principal de Clientes se divide em duas tabelas específicas: Pessoa Física (CPF) e Pessoa Jurídica (CNPJ). Isso garante que um cliente seja apenas um dos tipos, evitando campos nulos e dados inconsistentes.

Gestão de Pagamentos Flexível: Criei uma tabela dedicada para Meios de Pagamento. Agora, o sistema permite que um único cliente cadastre e gerencie múltiplas formas de pagamento (como cartões, PIX ou boletos), em vez de ficar limitado a apenas uma opção.

Módulo de Entregas e Logística: Adicionei uma tabela de Entrega vinculada aos pedidos. Ela é responsável por armazenar informações vitais de pós-venda, como o status da entrega (em trânsito, entregue, etc.) e o código de rastreio, permitindo o acompanhamento detalhado de cada envio.
