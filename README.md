# nassauTickets

## Descrição
O **nassauTickets** é um Sistema de Controle de Atendimento desenvolvido para um Laboratório de Análises Clínicas.

## Objetivo
O projeto tem como objetivo principal gerir a emissão, fila, chamada e atendimento de senhas. A aplicação consolida conhecimentos em desenvolvimento Web, integração de sistemas, banco de dados e trabalho de equipe com Git/GitHub. O sistema suporta três tipos de senhas (Prioritária, Geral e de Retirada de Exames) e segue regras de prioridade e fluxos de estado específicos.

## Tecnologias Utilizadas
* **Frontend:** React
* **Backend:** [Node.js 22 com Express]
* **Base de Dados:** MySQL 8.0

## Arquitetura e Visão Geral do Sistema
O sistema baseia-se numa arquitetura cliente-servidor (Frontend e Backend separados) e é operado por três agentes principais:
* **Agente Sistema (AS):** Executa as ações do sistema, comunica-se com a base de dados, atualiza o painel e emite senhas.
* **Agente Atendente (AA):** Chama o próximo cliente e realiza o atendimento no guiché. Possui login próprio e acesso a relatórios e gestão.
* **Agente Cliente (AC):** Interage anonimamente através de um totem para emitir a sua senha e acompanha o painel de chamadas.

## Configuração Necessária
Antes de iniciar, certifique-se de que tem instalado na sua máquina:
* Node.js
* MySQL 8.0

## Instruções de Instalação

1. Clone o repositório para a sua máquina:
   ```bash
   git clone [https://github.com/](https://github.com/)[seu-utilizador]/nassauTickets.git

2. Para executar o Frontend:
    npm run dev

3. Para executar o Backend:
    npm start

## Membros

* | Nome | Matrícula | Papel |
* | Maria Giulia Souza Martins | 01822824 | Scrum Master |
* | Pedro Ferreira da Rocha Falcão | 01830497 | Documentador |
* | Caique Barbosa Pimentel de Andrade | 01799401 | Desenvolvedor |
* | Gabriel Morais Justino | 01806064 | Desenvolvedor |
* | Henrique Gomes Gonzaga Diniz | 01796760 | Testador |
* | José Edeilson da Silva Júnior | 01805046 | Testador |
