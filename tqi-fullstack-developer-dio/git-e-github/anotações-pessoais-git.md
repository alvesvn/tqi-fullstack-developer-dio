# Funcionamento do Git e GitHub. 

**Principais tópicos:** 

- Lista de comandos úteis
- Diferença de Git e GitHub
- SHA1 
- Objetos fundamentais
- Sistema distribuído. 
- Segurança. 



_________

**Alguns comandos:** 

- **DIR** - lista de diretórios na pasta que estamos situados. 
- **CD** - possibilita que você navegue entre as páginas. 
- **CD NOME DA PASTA** - entra na pasta com o nome que você digitou. 
- **CD ..** - volta uma pasta
- **CLS** - limpa o terminal - GIT: **CTRL + L**
- **TAB** - auto complete. 
- **MKDIR NOME DA PASTA** - criar uma pasta 
- **Silence on sucess** - ok! tudo certo. 
- **ECHO - texto >hello.txt** - criar um conteúdo
- **DEL** - deleta os arquivos dentro de uma pasta
- **RMDIR** - deleta tudo 



**Git/GitHub: qual a diferença?** 

**Git** é um software VCS local que permite aos desenvolvedores salvar snapshots **de** seus projetos ao longo **do** tempo. Geralmente é melhor para uso individual. **GitHub** é uma plataforma baseada na web que incorpora os recursos **de** controle **de** versões **do GitHub** para que possam ser usados colaborativamente.



**SHA1 e SEGURANÇA:**  Em criptografia, SHA-1 é uma função de dispersão criptográfica (ou função hash criptográfica) projetada pela Agência de Segurança Nacional dos Estados Unidos e é um Padrão Federal de Processamento de Informação dos Estados Unidos publicado pelo Instituto Nacional de Padrões e Tecnologia (NIST).

Gera um conjunto de caracteres de segurança identificador de 40 dígitos. Por conta de todos esses detalhes, versões distribuídas, ele se torna seguro.

**Exemplo:** 

- É criado um arquivo de texto, para esse arquivo é gerado um identificador de 40 dígitos (SHA1).

- Alteramos o arquivo de texto - gera um novo identificador de 40 dígitos (SHA1).

- Alteramos o arquivo novamente deixando o conteúdo como o primeiro arquivo criado - o código identificador de 40 dígitos (SHA1) retorna para o código inicial do arquivo. 

  

**SISTEMA DISTRIBUÍDO**

O **Git** é um **Sistema** de Controle de Versão **Distribuído** que evita que alterações realizadas em um projeto modifiquem o código-fonte. Criado para facilitar a vida do desenvolvedor. 



___________________________________________________________________________________________________________________________________

### Segunda aula: Git e GitHub - DIO. 

**Principais tópicos:**  

- Blobs
- Trees
- Commits 



**Blobs:** contém metadados dentro dele: tipo, tamanho, conteúdo. 

**Trees:** armazena e aponta para os blobs. 

Dentro das trees pode conter: blobs, tree. 

**Commit:** junta tudo, também possui criptografia de identificador. 



Caso você altere um documento do blob que é apontado para uma tree - reflete na tree que também reflete no commit. 

**COMMIT > TREE > BLOBS** 



_____________________________________

# CHAVE E SSH



O SSH é um protocolo de rede que permite que a conexão com determinados servidores por meio de uma comunicação criptografada, trazendo mais segurança para as transações de dados.

Mais detalhes de como configurar e adicionar novas chaves:

[![Google](https://img.shields.io/badge/Google_chrome-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white)](https://dev.to/dxwebster/como-conectar-ao-github-com-chaves-ssh-1i41)



**O que é um token de acesso?**

Um token de acesso, de forma simplificada, seria uma chave em um formato como `e962e591092e9830f8ec6c2a4166e8655b768e88` que te permite ter acesso a algo. No caso do Github você usaria uma chave assim no lugar da senha da sua conta ao executar operações pela linha de comando ou na API.

**Qual a vantagem em relação à minha senha?**

A sua senha dá acesso a tudo em sua conta. Quem tiver sua senha pode apagar seus repositórios, alterar seus dados, fazer commits para qualquer repositório privado onde você possui permissões, apagar sua conta, etc. Concorda que se sua senha vazar ou se alguém tiver acesso a uma máquina onde sua senha está salva, esta pessoa terá muito poder?

Complemente as informações no link abaixo: 

[![Google](https://img.shields.io/badge/Google_chrome-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white)](https://www.treinaweb.com.br/blog/github-pare-com-as-senhas-e-utilize-tokens-de-acesso)



_______

# Entendendo os conceitos 

- Tracked 

- Untracked

- Staged

- Commit

- Unmodified 

- Modified 

  

![Git - Recording Changes to the Repository](https://git-scm.com/book/en/v2/images/lifecycle.png)



**Anotações pessoais para não esquecer:** 

- Quando criamos um arquivo, ex: strogonoff.md - Ele está UNTRACKED - o git ainda não conhece ele, acabou de ser criado. 
- Quando usamos o comando GIT ADD . - o arquivo sai do untracked e vai para o staged - área na qual ele está esperando algum comando. 
- Staged - o arquivo esta se preparando para fazer parte de um COMMIT.
- Commit - volta para unmodified. 
- Arquivo do repositório que não foi modificado - MODIFIED
- Modified - se executarmos o comando GIT ADD . - ele também vai para o staged. 
- Se tivermos um arquivo modified e removemos ele, o mesmo volta para untracked. 



**O QUE SÃO REPOSITÓRIOS.** 


Servidor - remote repository

Ambiente de desenvolvimento - working directory - staging area - local repository 


Repositório local - composto por commits. 



**ADICIONANDO NO REPOSITORIO REMOTO** 

git remote add origin LINK

git remote -v - verifica os arquivos 

git push origin master - empurra o arquivo para o remoto. 



**RESOLVENDO CONFLITOS.** 

o github vai sinalizar para você que tem duas alterações na mesma linha 
e a vai aparecer um documento estranho. 

Você terá que decidir manualmente. 

Após vc organizar o documento e decidir as alterações

você ira realizar os comandos. 

git status 

dois arquivos booth modified. 

- git add * 
- git commit -m "resolve conflitos" 

commit será realizado e você ira levar a versão corrigida 
para o remoto com os comandos a seguir: 

- git push origin master 



**Como baixar um repositório**

- Localize um repositório
- Copie o link (Clone with HTTPS)
- $ git clone https://.......



_______________________



# Git e GitHub para iniciantes – Tutorial completo



Tutorial completo que encontrei na internet para iniciantes, muito bom!!! Vale a pena a leitura. 

Clique no link abaixo:

[![Google](https://img.shields.io/badge/Google_chrome-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white)](https://fullcycle.com.br/git-e-github/)

