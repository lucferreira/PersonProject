Arquivo para teste de utilização do git
Mais um teste de inclusão
########################################
Treinamento git:

Serviço de Web compartilhado para projetos que utilizam o git para versionamento.
Github não é o mesmo que o git
github - repositório na web onde você guarda seus projetos versionados pelo git

untracked  -> Não marcado - é o momento em que o arquivo foi adicionado no repositório, porém não foi visualizado pelo git.
unmodified -> Não foi modificado, existe no git, mas não hoube modidifcação
modified -> depois de modificado ele fica com esse status
staged -> Momento em que o momento vai ficar sendo avisado, no moememtno que a versão ficar fechada suba esse arquivo.
Depois de que é criado e subida da versão, o arquivo volta para unmodified.

Comandos do Git:
- git status => visualizar informações do repositório.
- git diff => mostra as alterações antes de você comitar
- git show número do branch => mostra informações sobre aquele número do branch
- git log author "" => Filtra pelo autor do commit
<<<<<<< HEAD

- git diff --name-only
- git checkout => Retorna o arquivo para versão anterior.
=======
- git diff --name-only

- git reset --hard (+ identificação do commit) volta tudo ao estado anterior com status unmodifed
- git reset --soft (+ identificação do commit)
- git reset --mixed (+ identificação do commit)
- git push -u (para não ter que digitar novamente na próxima vez que utilizar o comando)
- git push -u origin master => Vem do branch padrão (master) e volta para origin (pasta local)
- (branch) -> Repositório master por default
- Fork => Clicar no botão do fork no site do github => copia do repostório original para um outro projeto. Isso é feito para projetos que não são seus.
Assim que modificado é possível enviar.
- git checkout - b 'nome do branch'
- git branch informa todos os seus branchs (* é aquele que está sendo usado no momento).
- git branch -D => apaga um branch
É bom para evitar conflitos com arquivos (guarda as modificações), faz o comando e depois faz o pull de arquivo
- git stach => Pausa a modificação do arquivo relacionado aquele branch
- git stash --apply => aplica as modificações no arquivo.
- git stash list => lista todas as modificações utilizando o stash
- git stash clear => Apaga todos os stashs criados
- criando atalhos com o git config:
ex: git config --global alias.s status
ex: git config --global alias.b branch
Utilizando tags para quem trabalha com bibliotecas:
git tag -a 1.0.0 -m "Primeira versão"
git tag -a 1.0.2 -m "Segunda versão"
git tag -a 1.0.3 -m "Terceira versão"
Informações sobre o comando revert (utilidade - reverte as mudanças feitas anteriormente, pode dar um checkout para ver o que aconteceu. Ele 
para não apagar as modificações que você fez):
git revert id do commit.
Apagar a tag do repositorio remoto
Local: git tag -d versão da tag -> mas isso não apaga do diretório remoto
git push origin : versão da tag que você quer apagar
git push origin : nome do branch



=======
- git diff --name-only
>>>>>>> ccb2164a59e402efc9ef0f9f241ce556f4f8c3cc
