Comandos com * (Aparecem nos vídeos)

Videos Utilizados para Aprender Git e GitHub:
1.https://www.youtube.com/watch?v=DqTITcMq68k
2.https://www.youtube.com/watch?v=UBAX-13g8OM&t=1s

Site com Diversos comandos para git:
1.https://gist.github.com/leocomelli/2545add34e4fec21ec16

Listas de comandos para o Git:

1- git init (Iniciar um repositório git vazio)

2- Adicionar arquivo/diretório (add)

2.1- git add meu_arquivo.txt (Adicionar um arquivo em específico)*
2.2- git add meu_diretorio (Adicionar um diretório em específico)
2.3- git add . (Adicionar todos os arquivos/diretórios)*	
2.4- git add -f arquivo_no_gitignore.txt (Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório))

3- Comitar arquivo/diretório (commit)

3.1- git commit meu_arquivo.txt (Comitar um arquivo)
3.2- git commit meu_arquivo.txt meu_outro_arquivo.txt (Comitar vários arquivos)
3.3- git commit -m "minha mensagem de commit" (Comitar informando mensagem)*

4- git status (Verificar estado dos arquivos/diretórios)*

5- git remote add origin git@github.com:xxxxx/xxxx.git (Vincular repositório local com um repositório remoto)*

6- Enviar arquivos/diretórios para o repositório remoto (Push)

6.1- git push -u origin master (O primeiro push de um repositório deve conter o nome do repositório remoto e o branch)*
6.2- git push (Os demais pushes não precisam dessa informação)

7- Branch

7.1- git branch -M "main" (Alterando Master para Main)*
7.2- git checkout -b "nome da nova branch" (Criar um novo branch e troca)*
7.3- git checkout "nome da branch" (Voltar para o branch em questão)*

8- git merge bug-123 (Resolver merge entre os branches)* - (Para realizar o merge, é necessário estar no branch que deverá receber as alterações. O merge pode automático ou manual. O merge automático será feito em arquivos textos que não sofreram alterações nas mesmas linhas, já o merge manual será feito em arquivos textos que sofreram alterações nas mesmas linhas)

9- git clone git@github.com:xxxxx/xxxxx.git (Clonar um repositório remoto já existente)*

10- Atualizar repositório local de acordo com o repositório remoto (pull)

10.1- git pull (Atualizar os arquivos no branch atual)*