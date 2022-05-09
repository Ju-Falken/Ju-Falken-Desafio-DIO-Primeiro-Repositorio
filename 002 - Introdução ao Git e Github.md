\#Introdução ao Git e Github

- \*\*Git\*\* é um software aberto de versionamento de código, podendo também ser usado para outros fins - como produção de artigos. Software extremamente seguro, todos os arquivos passam por encriptação e são sempre lidos pelo software, que identifica se foram realizadas alterações nos arquivos ou diretórios, gerando nova chave de encriptação;
- \*\*Github\*\* é um local remoto para armazenamento de repositórios. Está bastante conectado ao Git, havendo comandos diretamente no Git que puxam e empurram repositórios para o Github. É uma plataforma muito utilizada por desenvolvedores para tornarem públicos os seus projetos, permitindo que outras pessoas participem do desenvolvimento e façam alterações em seus códigos. É utilizada também como portfólio de projetos com fim comercial e é também utilizada por empresas no processo de conhecer mais sobre aquela pessoa e a forma como ela vem desenvolvendo seu código ao longo do tempo;
- \*\*Comandos básicos\*\*: (há diferença entre Windows e Linux)
- dir - retorna o local atual dentro do PC;
- cd - para viajar entre pastas
- cd .. - retornar para pasta anterior
- cls/ctrl+l - limpar área de comando
- tab - completar palavras
- mkdir - cria pasta
- echo - escreve no terminal - é bastante utilizado concomitantemente com flags - usando echo > <filename> irá redirecionar o texto para este documento, caso ele não exista, será criado um documento;
- del - deleta arquivos dentro de uma pasta, mas não deleta a pasta;
- rmdir - deleta a pasta e os arquivos nela;

- \*\*Comandos no Git\*\* devem vir com "git" antes do comando:
- git init + nome da pasta - inicia o git naquela pasta (quando criamos um arquivo no PC, ele não foi visualizado pelo git ainda, então damos esse comando para que o Git tome conhecimento deste arquivo e conheça o conteúdo dele - acho que aqui é gerado um sha1 pra esse doc) - cria uma pasta oculta .git;
- ls -a: apresenta os arquivos ocultos de uma pasta;
- Flags  modificam o significado de um determinado comando (-a é uma flag, -m também)
- git add + nomearquivo para determinado arquivo. Para adicionar todos os arquivos da pasta ao git, usa-se . ou \*; manda os arquivos para staged;
- git commit -m (flag do git commit que adiciona mensagem) + "MENSAGEM QUE ESTARÁ NO COMMIT"
- git status - devolve o estado dos arquivos dentro do git;
- Git remote -v: para saber o nome dos repositórios no repositório remoto;

- SHA1 - tipo de encriptação utilizada pelo Git - 40 caracteres. Para saber qual o SHA1 de um arquivo: openssl sha1 nomearquivo
- \*\*Objetos do Git\*\* - ####ESSE ASSUNTO EU PRECISO ME APROFUNDAR
- Blobs
- Trees - armazena blobs;
- Commits - Traz parente (versão anterior), mensagem que dá significado as alterações realizadas, nome dos arquivo, início do sha1 do commit, autor, timestamp;

- \*\*Estado dos arquivos no Git\*\*:
- Untracked - um arquivo que o Git não conhece ainda; arquivo recém criado no PC;
- Tracked: Git já tem conhecimento
- unmodified - não foi modificado desde o momento que o Git ficou sabendo dele;
- modified - sofreu alguma modificação;
- staged - arquivo pronto para ser comitado, empurrado;
- Ambiente de desenvolvimento (PC)
- Working Directory - pasta onde estão nossos arquivos;
- Staging Area - local onde os arquivos ficam para receberem ações como serem comitados;
- Local repository - onde o arquivo fica depois de ter sido comitado;
- Servidor
- Remote repository - Nuvem, Github;