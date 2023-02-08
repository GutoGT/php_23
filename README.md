# php_23
1 verificar se estamos no ubuntu
2 FIle -> open folder
2.1 - apagao conteudo 
2.2 - informa o caminho /var/www/html
2.3 - abre essa pasta (enter ou clickando com o mause em html)
3 - terminal, novo terminal
4 - no terminal executa o comando: git clone LINK_DO_REPOSITORIO (github) 
5 - informar o caminho /var/www/html/php_23
5.1 - abre essa pasta (com enter ou clickando com mause com mouse em html)
6 - configurar o git (git email e o git name da pagina 4 da apostila) 
7 - verificar se  o apache esta rodando/executando
7.1 - acessar o navegador com localhost ou 127.0.0.1 (deve aparecer a configuracao inicialdo apache) .
7.2 - sudo service apache2 status (apache is runing)
7.3 - sudo service apche2 start .
7.4 - executar os passos 7.1 e 7.2 .
 ## para salvar no github
 1 - git add . (onde . é todos os arquivos ou especificar por nome ex.: git add index.php)
 2 - git commit -m "DESCREVER O QUE FOI FEITO"
 3 - git push
 4 - verificar no github se ficou salvo.

teste teste 1 . teste teste 2 .
teste teste 3 . teste teste 4 .
teste teste 5 . 
## para o mege 
1 - git checkout NOME_BRENCH
2 - git pull (obter as atualizacoes)
3 - git merge NOME_BRENCH_DA_TRAZER_AS_MUDANCAS
  EX:
     estamos na brench *develop* e queremos levar para a master/main
      1 - git checkout *master*
      2 - git pull (master)
      3 - git merge *develop*
      4 - resolve conflitos se houver 
      4.1 - Com conflito: git add . e git commit -m "...."
      4.2 - Sem conflito: so executar o push
      5 - git push

      Estamos na Brench *master/main* e queremos levar as mudancas para a develop
      1 - git checkout *develop*
      2 - git pull (develop)
      3 - git merge *master/main*
      4 - resolve conflitos se houver 
      4.1 - Com conflito :git add . e git commit -m "...."
      4.2 - Sem conflito: so executar o push
      5 - git push
          