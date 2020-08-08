# ConfigVsCodeProgress4GL
* Configuração do VsCode para utilização do Progress 4GL
*
* Guilherme Moles 24/07/2020

## 📑 Índice

- [Sobre a Configuração](#-sobre-a-configuracao)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Executar esse projeto no seu computador](#Executar-esse-projeto-no-seu-computador)
- [Licença](#-licença)

## 💡 Sobre a Configuração

Configuração da Extenção do VSCode OpenEdge ABL - Camicas Christophe

## 🚀 Tecnologias utilizadas

Aconfiguração foi desenvolvido utilizando as seguintes tecnologias:

- Json
- Progress 4GL

## 📥 Executar essa configuração no seu computador

- Clonar Repositório: `git clone https://github.com/GuilhermeMoles/ConfigVsCodeProgress4GL.git`

OBS: Antes de configurar o ambiente verificar se o arquivo .openedge.json trocou o "." ponto inicial por "_" 
<br/> as vezes ao baixar o pacote do Google Drive ele faz isso, portanto se o arquivo ficou "_openedge.json" renomear para 
<br/> ".openedge.json".
<br/>
<br/> 1º. Passo - Copiar a pasta VsCodeConfig com os arquivos de configuração para o C:\
<br/> 2º. Passo - Baixar e Instalar o VS Code no link `https://code.visualstudio.com/download`
<br/> 3º. Passo - Adcionar a Extendão "OpenEdge ABL 1.1.6" do autor Camicas Christophe
<br/> 4º. Passo - Clicar em "File" "Open Workspace..." e abrir o arquivo de configuração do 
<br/>             workspace C:/VsCodeConfig/config.code-workspace
<br/> 5º. Passo - Configurar seu ambiente progress no arquivo JSON C:\VsCodeConfig\openedge.json
<br/>             Nesse arquivo é possivel configurar:
<br/>		      Propath         : Aqui que será definido o propath utilizado pela extensão.
<br/>			  DLC	          : Pasta do Progress, geralmente C:/Progress/OpenEdge ou C:/dlc102
<br/>			  ParameterFiles  : PF de configuração das conexões com os bancos, deixei uma PF
<br/>                               bem simples como padrão para você configurar sua conexão.
<br/>                               StartupProcedure: Arquivo .p que será executado todas as vezes que você rodar
<br/>                               algum programa pelo VS Code.
<br/> 
<br/> Após Finalizar essa configuração você ja pode checar a sintax com Shift F2 e realizar execução de programas com o F2.


## 📕 Licença

Todos os arquivos incluídos aqui, incluindo este _README_, estão sob [Licença MIT](./LICENSE).<br>
Criado por [Guilherme Moles](https://github.com/GuilhermeMoles)
