# Dona Neide
Objetivo do Sistema: Organizar o
recebimento e registro de encomendas
de bolos (nome, telefone, sabor e
data/hora de entrega), eliminando a
dependência do caderno físico. O
sistema aplica automaticamente uma
taxa de urgência de 30% para pedidos
com prazo inferior a 24 horas e
oferece uma interface acessível, com
fontes em tamanho ampliado e paleta
de cores em Rosa Bebê e Branco.

CLIENTE
id_cliente (PK)
nome
telefone

ENCOMENDA
id_encomenda (PK)
sabor_bolo
data_pedido
data_entrega
valor_base
eh_urgente
taxa_urgencia
valor_total
status_pedido
id_cliente (FK)

PAGAMENTO
id_pagamento (PK)
forma_pagamento
valor_pago
status_pagamento
id_encomenda (FK)
