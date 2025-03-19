# Gerador de Comandos Nokia-ZTE

Este projeto é um gerador de comandos para configuração de equipamentos Nokia e ZTE, desenvolvido para facilitar o trabalho da equipe de Backoffice de Redes.

## Funcionalidades

*   **Interface Intuitiva:** Formulário simples para inserir informações de configuração.
*   **Geração Automática de Comandos:** Gera os comandos necessários para configurar os equipamentos com base nos dados inseridos.
*   **Cópia Facilitada:** Botões para copiar os comandos gerados para a área de transferência.
*   **Design Responsivo:** Layout que se adapta a diferentes tamanhos de tela.

## Como Usar

1.  Abra o arquivo `index.html` em seu navegador.
2.  Preencha os campos do formulário com as informações de configuração do equipamento.
3.  Clique no botão "Gerar Comandos".
4.  Os comandos gerados serão exibidos na seção de resultados.
5.  Clique nos botões "Copiar" para copiar os comandos desejados para a área de transferência.

## Campos do Formulário

*   **Usuário PPPoE:** Nome de usuário PPPoE para a conexão.
*   **Serial:** Número de série do equipamento.
*   **Slot:** Slot do equipamento.
*   **Porta:** Porta do equipamento.
*   **ID:** ID do equipamento.

## Comandos Gerados

A seção de comandos gerados exibe os seguintes comandos:

*   `configure terminal`
*   Comandos de interface `gpon-olt_1/...`
*   Comandos de interface `gpon-onu_1/...`
*   Comandos `pon-onu-mng gpon-onu_1/...`

**Observação:** A senha PPPoE (`{{SENHA_PPPOE}}`) deve ser substituída pela senha real no comando gerado.

## Créditos

*   **Desenvolvedores:** Brunno Leandro, Equipe Backoffice Redes da BH e Gabriel Souza.
*   **Design:** Baseado em um template com paleta de cores moderna e responsiva.

## Licença

Todos os direitos reservados.

## Imagem de Exemplo

![Imagem do Projeto](https://proxxima.net/themes/milha-telecom/assets/img/bgs/people-working.jpg)

## Contribuição

Este projeto foi desenvolvido para uso interno da equipe. Contribuições externas não serão aceitas no momento.
