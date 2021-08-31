# ConfigVsCodeProgress4GL
* Configuração do VsCode para utilização do Progress 4GL
* Guilherme Moles 24/07/2020

## 📑 Índice

- [Sobre a Configuração](#-sobre-a-configuracao)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Executar essa configuração no seu computador](#Executar-essa-configuração-no-seu-computador)
- [Licença](#-licença)

## 💡 Sobre a Configuração

Configuração da Extenção do VSCode OpenEdge ABL - Camicas Christophe

## 🚀 Tecnologias utilizadas

A configuração foi realizada utilizando as seguintes tecnologias:

- Json
- Progress 4GL

## 📥 Executar essa configuração no seu computador

- Acessar o C: e Clonar o Repositório: `git clone https://github.com/gmoles/ConfigVsCodeProgress4GL.git`

OBS: Antes de configurar o ambiente verificar se o arquivo .openedge.json trocou o "." ponto inicial por "_" 
 as vezes ao baixar o pacote do Google Drive ele faz isso, portanto se o arquivo ficou "_openedge.json" renomear para 
 ".openedge.json".
```sh
- 1º. Passo - Acessar o C: e Clonar o Repositório
- 2º. Passo - Baixar e Instalar o VS Code no link `https://code.visualstudio.com/download`
- 3º. Passo - Adcionar a Extendão "OpenEdge ABL v1.2.0" do autor Camicas Christophe
- 4º. Passo - Clicar em "File" "Open Workspace..." e abrir o arquivo de configuração do workspace 
	      C:/VsCodeConfig/config.code-workspace
- 5º. Passo - Configurar seu ambiente progress no arquivo JSON C:\VsCodeConfig\openedge.json
              Nesse arquivo é possivel configurar:
	      Propath         : Aqui que será definido o propath utilizado pela extensão.
	      DLC	      : Pasta do Progress, geralmente C:/Progress/OpenEdge ou C:/dlc102
	      ParameterFiles  : PF de configuração das conexões com os bancos, deixei uma PF
                                bem simples como padrão para você configurar sua conexão.
                                StartupProcedure: Arquivo .p que será executado todas as vezes que você rodar
                                algum programa pelo VS Code.
```
Após Finalizar essa configuração você ja pode checar a sintax com Shift F2 e realizar execução de programas com o F2.

## 📕 Licença

Todos os arquivos incluídos aqui, incluindo este _README_, estão sob [Licença MIT](./LICENSE).<br>
Criado por [Guilherme Moles](https://github.com/GuilhermeMoles)
