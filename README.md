# calcula-frete-cep
Consulta Endereço via CEP

O programa consiste em uma API REST de consulta de endereço e cálculo de frete para um determinado CEP. Para a busca do endereço do CEP, o programa faz uma pesquisa utilizando a API VIA CEP, conforme a documentação https://viacep.com.br/. O valor do frete é fixo de acordo com as regiões do Brasil: Sudeste (R$ 7,85), Centro-Oeste (R$ 12,50), Nordeste (R$ 15,98), Sul (R$ 17,30) e Norte (R$ 20,83). O CEP é obrigatório e pode ser passado com ou sem máscara na entrada e se o CEP não for encontrado uma mensagem informativa deve ser retornada para o usuário.

Foram utilizados no desenvolvimento 

•	Java 11

•	Spring boot

•	API REST Template

•	Documentação Swagger 

•	Testes unitários JUnit5
