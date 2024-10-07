# Aplicação Node-RED: Catálogo de Corretoras e Buscador de CEP

Esta aplicação foi desenvolvida como parte de um teste técnico e consiste em duas funcionalidades principais: um catálogo de corretoras utilizando a BrazilAPI e um buscador de CEP.

## Funcionalidades

1. **Catálogo de Corretoras**
   - Uma página da web que lista todas as corretoras disponíveis na BrazilAPI no formato:
     ```
     "${Nome} - ${Cidade} / ${CNPJ}"
     ```

2. **Buscador de CEP**
   - Uma página da web que permite ao usuário buscar detalhes de um CEP usando a BrazilAPI.
   - **Opção 1:** O CEP pode ser inserido como um parâmetro de rota.
   - **Opção 2:** O CEP pode ser inserido em um campo de entrada.

### Pontos Extras
- Ambas as opções de buscador de CEP foram implementadas.
- A aplicação inclui um bom estilo, utilizando [nome do framework ou biblioteca] para estilização (se aplicável).

## Tecnologias Utilizadas

- Node-RED
- BrazilAPI

## Pré-requisitos

Antes de executar a aplicação, verifique se você possui o seguinte instalado:

- Node.js (versão x.x.x)
- Node-RED (versão x.x.x)

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/SandlerJr/teste.git
