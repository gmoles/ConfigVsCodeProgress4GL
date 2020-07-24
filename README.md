# ConfigVsCodeProgress4GL
* Configuração do VsCode para utilização do Progress 4GL
*
* Guilherme Moles 24/07/2020


OBS: Antes de configurar o ambiente verificar se o arquivo .openedge.json trocou o "." ponto inicial por "_" 
as vezes ao baixar o pacote do Google Drive ele faz isso, portanto se o arquivo ficou "_openedge.json" renomear para 
".openedge.json".

1º. Passo - Copiar a pasta VsCodeConfig com os arquivos de configuração para o C:\
2º. Passo - Baixar e Instalar o VS Code no link https://code.visualstudio.com/download
3º. Passo - Adcionar a Extendão "OpenEdge ABL 1.1.6" do autor Camicas Christophe
4º. Passo - Clicar em "File" "Open Workspace..." e abrir o arquivo de configuração do 
            workspace C:/VsCodeConfig/config.code-workspace
5º. Passo - Configurar seu ambiente progress no arquivo JSON C:\VsCodeConfig\openedge.json
            Nesse arquivo é possivel configurar:
			Propath         : Aqui que será definido o propath utilizado pela extensão.
			DLC				      : Pasta do Progress, geralmente C:/Progress/OpenEdge ou C:/dlc102
			ParameterFiles 	: PF de configuração das conexões com os bancos, deixei uma PF
                        bem simples como padrão para você configurar sua conexão.
                        StartupProcedure: Arquivo .p que será executado todas as vezes que você rodar
                        algum programa pelo VS Code.

Após Finalizar essa configuração você ja pode checar a sintax com Shift F2 e realizar execução de programas com o F2.
