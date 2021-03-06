# Equipe
* Pedro Lino
* Gabriel Costa
* Gustavo Henrique
* Rafael Lancry
* Guilherme Lopes

# Descrição do Projeto
Video game de RPG em pixel art de exploração, com sistema de batalha em turnos utilizando a lib gráfica RayLib, baseado nas mecânicas de Earthbound, Pokémon, Final Fantasy, ambientado no Porto Digital/Cesar School com 4 personagens principais onde terão que investigar uma invasão alienígena que pretende roubar as tecnologias aqui produzidas e também terão que defender o Porto Digital das ameaças dessa invasão.

# Instrução para instalar o RayLib para VSCODE via MS-VCPKG

Caso ainda não tenha o RayLib instalado, siga os seguintes comandos:
* Garanta ter o git e vscode instalado em sua máquina 
* Usar Windows Terminal (de preferência) ou PowerShell

Abra o terminal (no root padrão do sistema)

<code>
  1) git clone https://github.com/Microsoft/vcpkg.git
</code>
<br>
<code>
  2) cd vcpkg
</code>
<br>
<code>
  3) .\bootstrap-vcpkg.bat
</code>
<br>
<code>
  4) .\vcpkg integrate install
</code>
<br>
<code>
  5) .\vcpkg install raylib  
</code>
<br>
<br>

Tendo todos os arquivos instalados sem erros, o RayLib.h estará compilado no sistema.

Clone o repositório numa nova pasta com:

<code>git clone https://github.com/DjdogeGamer/ProjetoPIF</code>

Dentro do VS Code, Apenas selecione o código do "main.c" e pressione "F5" para rodar o Makefile. (não execute diretamente pelo "play")
