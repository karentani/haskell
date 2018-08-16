Aulas de Haskell no C9.

Configuracoes iniciais apos criar um workspace > blank:

 No terminal do linux

 # sudo add-apt-repository ppa:hvr/ghc
 # sudo apt-get update
 # sudo apt-get install ghc-8.0.2
 # vi ~/.bashrc

 Inserir ao final do arquivo ( i - inserir; :wq - salvar e sair)

   export PATH="$HOME/.cabal/bin:/opt/cabal/1.22/bin:/opt/ghc/8.0.2/bin:$PATH"

 # source ~/.bashrc

 Para iniciar o Prelude 

 # ghci
