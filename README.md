# siimis

Hierarquia de Status

Evento 
	-> "Elaboração" dataEnvio = NULL
	-> "Enviado" dataEnvio = NOT NULL
	-> "Cultura Z" = dataEnvio = NOT NULL AND Liberado NOT NULL
	
Pedido de Contratação 
	-> "Elaboração" dataEnvio = NULL (não visível no sistema)
	-> "Em análise" dataEnvio = NOT NULL (vísivel no sistema)
	-> "Liberado"  dataEnvio = NOT NULL AND liberado = NOT NULL
	-> "Empenhado" dataEnvio = NOT NULL AND liberado NOT NULL AND empenhado = NOT NULL

