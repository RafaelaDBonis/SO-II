# SO-II
Anotações das aulas de Sistemas Operacionais 

# Tópicos
  - [comandos](#comandos)
  - [BASH](#bash)
    
<h4>Aula do dia 14/08/2023 - Introdução VM (máquina virtual)</h4>

# Comandos:

  * clear -> limpa tela
  * ls -> exibe arquivos e pastas
  * cd -> entra na pasta
  * cd.. -> sai da pasta
  * mkdir -> cria pasta
  * touch -> cria arquivo
  * cat -> exibe conteúdo do arquivo
  * rmdir -> apaga pasta
  * rm -rf -> apagar pasta com conteúdo
  * man -> manual do comando
      *Ex: man touch -> manual do touch
          q (quit) -> sair do manual
  * pwd -> caminho da pasta atual
  * cd~ -> ir para pasta d usuário
  * / -> raiz do disco (C:)
  
# BASH

Bourne-Again SHell -> BASH
-  O linux é um SO modular, seu modulo principal é o núcleo (kernel) e depois dele existe a interface (shell/casca), por meio do shell o usuário interage com o kernel.
-  Kernel é um conjunto de aplicativos para se realizar funções de hardware e memoria por exemplo.
-  BASH é um shell renascido, mais moderno. Ele permite arquivos digitados diretamente e também mostra o conteúdo dos arquivos dentro de script também 

Para verificar se um SO tem algum BASH basta entrar no terminal e digitar os comandos cat/etc/shells

na aula do dia 28/08

- Crie um arquivo de script com touch aula.sh
- Para abrir o arquivo use um editor de texto
  - nano aula.sh
  - #!/bin/bash
  - Pule uma linha e escreva echo"teste"
    
No nano, salve o arquivo Ctrl + X




