## Principais conceitos do GitHub

* Repositório (Repository) – Um local onde os arquivos do projeto são armazenados e versionados. Pode ser público ou privado.

* Commit – Uma alteração salva no repositório, incluindo um histórico das mudanças.

* Branch – Uma ramificação do código, permitindo que alterações sejam feitas sem afetar a versão principal.

* Merge – Combinação de alterações de uma branch para outra.

* Pull Request (PR) – Solicitação para revisar e mesclar mudanças de uma branch para outra.

* Fork – Cópia de um repositório para sua conta, permitindo alterações sem afetar o original.

* Clone – Cópia local de um repositório GitHub para trabalhar offline.

* Push – Envia mudanças locais para o repositório remoto.

* Pull – Atualiza a cópia local com mudanças do repositório remoto.

* Issues – Funcionalidade para rastrear bugs, melhorias ou tarefas dentro do repositório.

* Actions – Automação de fluxos de trabalho, como testes e deploys.



Arquivos .md = arquivo tipo texto para anotações


    git config --global user.name

        confere o nome do usuário logado

-----------------

    git config --global user.email

        confere o email logado

-----------------

    git init

        registra que o repositório foi inicializado

-----------------

    git status 

        mostra os status dos commits

-----------------

    git config --list

        lista de repositórios?? 
        pra sair dele basta apertar q

-----------------

    git commit -m "Corrige bug na validação de CPF"

        usado para fornecer uma mensagem de compromisso para um commit

-----------------

    git remote -v

        indica se tem alguma origem remota


-----------------

    git remote add origin https://github.com/marina-servo-morales/potencia-feminina-github.git

        comando que peguei do repositório criado no github


-----------------

    cd ../

        volta pra pasta raiz

-----------------

    ls

        lista o que tem dentro dele

-----------------

    git add .
        adiciona todos os arquivos

    ou pode fazer git add caminho específico do arquivo