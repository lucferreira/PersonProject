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

=======
- git diff --name-only
>>>>>>> ccb2164a59e402efc9ef0f9f241ce556f4f8c3cc
