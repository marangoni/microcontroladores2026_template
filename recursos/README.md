# Recursos da disciplina

Esta pasta reúne links e orientações para instalação das ferramentas utilizadas na disciplina de Microcontroladores.

## Ferramentas utilizadas

Ao longo das atividades, vocês deverão instalar e utilizar as seguintes ferramentas:

- **MPLAB X IDE**
- **Compilador XC8**
- **SimulIDE**

## 1. MPLAB X IDE

O MPLAB X IDE será utilizado como ambiente de desenvolvimento para edição, organização e compilação dos programas.

### Download oficial

Acesse a página oficial da Microchip:

- MPLAB X IDE: https://www.microchip.com/en-us/tools-resources/develop/mplab-x-ide

### Observações

- Baixe sempre a versão correspondente ao seu sistema operacional.
- Durante a instalação, mantenha as opções padrão, salvo orientação diferente do professor.
- Em Linux, o instalador normalmente é fornecido como arquivo compactado com instalador `.sh`.

## 2. Compilador XC8

O compilador XC8 será utilizado para compilar programas em C para microcontroladores suportados pela Microchip, incluindo a linha AVR utilizada em várias atividades da disciplina.

### Download oficial

Acesse a página oficial da Microchip:

- MPLAB XC8 Compiler: https://www.microchip.com/en-us/tools-resources/develop/mplab-xc-compilers/xc8

### Observações

- Instale a versão compatível com o seu sistema operacional.
- Para esta disciplina, utilizaremos a versão gratuita do compilador.
- Em geral, primeiro instala-se o MPLAB X IDE e, em seguida, o XC8.

## 3. SimulIDE

O SimulIDE será utilizado para simulação de circuitos e testes iniciais dos programas desenvolvidos em aula.

### Página oficial

- Repositório oficial do SimulIDE: https://github.com/SimulIDE/SimulIDE

### Observações

- Verifique na página do projeto a versão mais adequada para o seu sistema operacional.
- O SimulIDE é útil para testar rapidamente circuitos simples com microcontroladores, portas digitais, botões, LEDs e displays.
- Nem todos os recursos equivalem a uma simulação física completa; ele deve ser usado como ferramenta didática de apoio.

## Recomendações para instalação

Antes de instalar, recomenda-se:

1. verificar qual é o seu sistema operacional;
2. baixar os instaladores somente das páginas oficiais;
3. instalar primeiro o **MPLAB X IDE**;
4. instalar depois o **XC8**;
5. instalar o **SimulIDE** como ferramenta de simulação complementar.

## Orientações gerais para os estudantes

- Realizem a instalação com antecedência.
- Testem a abertura dos programas logo após a instalação.
- Confirmem se o MPLAB X reconhece o compilador XC8.
- Guardem os instaladores baixados, caso precisem reinstalar posteriormente.
- Em caso de erro, registrem a mensagem apresentada e comuniquem ao professor.

## Orientação resumida para Linux

### MPLAB X IDE
Após baixar o instalador para Linux:

1. extraia o arquivo baixado, se necessário;
2. abra um terminal na pasta onde está o instalador;
3. dê permissão de execução ao arquivo `.sh`;
4. execute o instalador.

Exemplo:

```bash
chmod +x nome-do-instalador.sh
sudo ./nome-do-instalador.sh
