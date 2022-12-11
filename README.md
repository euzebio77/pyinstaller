# pyinstaller

Pyinstaller é um biblioteca que serve para transformar um condigo em python em um programa executavel, a utilização desta biblioteca é bem simples, segue abaixo o passo a passo:

# instalação

windows:
pip install pyinstaller 

# como usar

Para utilizar esta biblioteca é necessario que voce siga dois tipos de padrões, segue abaixo:

Caso o programa que voce esta desenvolvendo tenha alguma interface, sera necessasrio que voce use o comando, pyinstaller --onefile -w 'nome do arquivo'.py

Caso o programa que voce esta desenvolvendo nao tenha interface, nao sera necessario utilizar o '-w', pyinstaller --onefile 'nome do arquivo'.py


# boa pratica

É indicado que antes de transformar o programa em executavel, você deve criar um ambiente virtual, para que o programa não fique extenso
