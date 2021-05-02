# dicasup
Sistema de cadastro de dicas
=====================
 COMO RODAR O PROJETO:
======================

1. CLONE O REPOSITORIO OU FAÇA DO DOWNLOAD
 
2. ABRA A PASTA DICAS NO SEU EDITOR PREFERIDO OU TERMINAL
3. NO TEMINAL  MUDE PARA A PASTA study  comando: cd study
4. SUBA UM SEVIDOR DE TEST 
    php artisan serve


5. ESSE PROJETO APONTA PAR UM BANCO DE DADOS CHAMADO *areaprivada*
   usuario *root*  sem senhas

6.  CRIE AS TABLEAS USANDO O COMANDO 
   php artisan migrate

7.  SE QUISER USAR OS USUARIOS QUE EU CRIEI USE O COMANDO
    php artisan db:seed --class=Usuario
    Os dados de criaçao de usario está no diretorio
    database/seeders/Usuario
    apos rodar o comando a primeira vez
    comente o usuario dois e descomente o primeiro e 
    rode novamente
    MAS PODE CRIAR SEUS PROPRIOS USUARIOS


8.  EU PUS DOIS USUARIOS DE TESTE 
    1.  user@gmail.com       senha: abc123
    2.  admin@gmai.com      senha: aaabbb
    

=======================================
   F U N C I O N A L I D A D E S

=======================================


1. AO VISITAR PODE VER TODOS AS DICAS [da mais recente pra mais atiga]
   
2. PODEMOS FILTRAR A ORDEM | PARA TER ACESOS A MAIS FUNCIONALIDADES DEVE CRIAR UMA CONTA

3. O USARIO PODE SE CADASTRAR E LOGAR

3. CADASTRADO ELE VAI PARA UMA AREA VIP E LA ELE PODE
   a. CRIRR UMA NOVA DICA
   b. VER TODOS TODAS SUAS DICAS
   c. EDITAR OU EXCLUIR UMA DICA CRIADA POR ELE
      ao editar é carregada todos os campos para o formulario
