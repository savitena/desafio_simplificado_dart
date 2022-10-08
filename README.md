# desafio_simplificado_dart

Foi solicitado a criação de um sistema de registros de empresas. Toda empresa nesse sistema deve ter um sócio associado a ela, que pode ser uma Pessoa Física ou uma Pessoa Jurídica.

Sobre as entidades:

Uma Empresa no sistema tem os seguintes dados: ID, Razão Social, Nome Fantasia, CNPJ, Endereço (Logradouro, Número, Complemento, Bairro, Estado e CEP), Telefone, Horário do Cadastro e Sócio.
Um Sócio tem os seguintes dados: Nome, CPF e Endereço (Logradouro, Número, Complemento, Bairro, Estado e CEP).

O sistema ao ser executado deve:

Cadastrar uma nova empresa; (FEITO)

Requisitos Obrigatórios:
O programa deve ser criado considerando os recursos disponíveis da Orientação à Objetos e boas práticas;
CPF e CNPJ são do tipo String, mas o input do usuário será apenas números;
Telefone é do tipo String, mas o input do usuário será apenas números, ex.: 81987654321;
CEP é do tipo String, mas o input do usuário será apenas números;
O ID deve ser único, para cada Empresa cadastrada.
Requisitos Desejáveis:

Todo sócio, deve saber validar seu documento CPF;
O horário de cadastro deve ser obtido automaticamente pelo sistema.
A impressão do conteúdo de uma empresa deve atender no mínimo a seguinte formatação:

ID: ca3e6c78-dae6-4629-b819-e5576c00f68b
CNPJ: 11.941.838/0001-04 Data Cadastro: 2022-08-31 22:37:17.921952
Razão Social: Elisa e Flávia Pães e Doces ME
Nome Fantasia: Pães e Doces
Telefone: (19) 9 8838-0630
Endereço: Rua Três, 338, Vila Industrial, Piracicaba/SP, 13.412-233
Sócio:
CPF: 763.679.800-08
Nome Completo: Mirella Kamilly Letícia Barbosa
Endereço: Rua Ulisses Bueno, 175, Vila Rosa, Aparecida de Goiânia/GO, 74.935-870
Notas:

Os dados usados para impressão foram gerados a partir do site: https://www.4devs.com.br
