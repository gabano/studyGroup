### O que é Git e GitHub
**Git** é um *sistema de controle de versão* amplamente utilizado para o desenvolvimento de softwares.
Ele é capaz de criar um registro de tudo que foi feito e alterado, visando manter a integridade dos dados e possibilitando
a colaboração entre vários autores/programadores. O Git trabalha com **repositórios** que é o lugar 
no qual se encontram os registros de todas as modificações realizadas. Um repositório pode ser bifurcado, dando
origem a uma nova forquilha ou **fork**. Cada forquilha armazena seu próprio histórico. Outros usuários podem fazer bifurcações de um repositório inteiro ou de entroncamentos específicos para realizar modificações em cima deles. 
Após realizar suas modificações,o programador pode submetê-las ao entroncamento principal do projeto (**pull request**)!

O GitHub é um servidor na WEB que trabalha com o Git e é capaz de hospedar projetos que utilizem esse tipo de controle de versão.
Além disso, diferentemente do Git o GitHub oferece um interface gráfica para os usuários, para que eles possam ver o que está sendo feito em termos de manipulação do projeto.

**Mas por que estamos utilizando o GitHub?**
A resposta curta: Porque ele eficaz quando se trata de  organizar arquivos que possuam código embutido e porque já existem outros StudyGroups, baseados em MozillaScienceLab.



### Criando uma conta no GitHub  
Criar uma conta no GitHub fácil e gratuito. Acesse https://github.com  e clique em Sing Up no canto superior direito.
Agora, preencha com os dados pedidos e clique em 'Create an Account'. Se tudo deu certo, você é redirecionado a uma pagina que oferece diversos tipos de planos, deixe-a como está. Agora, clique em "Finish Sing Up" para terminar o processo.
Vá para o seu endereço de e-mail e confirme a sua conta.


#### Criando uma forquilha e um entroncamento.
Com sua conta logada, acesse a página github.com/gabano/studyGroup e clique em fork. Isto criará uma cópia do repositório de estudos na sua conta. A partir daí você será capaz de manipular os arquivos e editá-los. Entretanto, uma ação sobre um arquivo somente tomará efeito em seu repositório. Para mesclá-la ao repositório original onde estão concentrados os arquivos, é necessário abrir um pull request. A melhor forma de manter um repositório 'limpo' é criar entroncamentos para alterações específicas, isto é, criar um _branch_ para cada bloco de alteração e fazer um _pull request_ a partir desse entroncamento.

#### Submetendo alterações em sua própria forquilha
Para editar um arquivo, primeiro vá ao arquivo que deseja editar... por exemplo o README.md. Clique em Edit. Faça as alterações e clique em Commit changes, o botão verde, no fim da página. Caso julgue necessário, crie um new branch e start a new pull request se for querer mesclá-lo a um ramo principal. 

**Exemplo prático**  
Adicionando-se à lista de membros!

Vá em seu fork do studyGroup, acesse a pasta _data, ela deve estar localizada em https://github.com/SEUUSUARIO/studyGroup/tree/gh-pages/_data.
Clique em **members.yml**, em seguida clique em Edit.  
Siga as instruções dentro do arquivo.  
Na área de commit changes, clique em _create a new branch and start a pull request_. Na caixa de texto, crie um nome descritivo para esse novo ramo... Sugestão: add-member-[seunome] e clique em Propose File Changes.

Nela, clique em Branch e na caixa de texto que aparece crie um novo branch chamado add-seunome (substituindo seunome pelo seu primeiro nome) e clique em **Create branch: add-seunome**.


#### Submetendo alterações em outros repositórios (pull request) 
Atenção: aqui eu falo rapidamente sobre pull-request, vamos ver na prática no nosso quadro de discussão.

Você também pode querer fazer alterações maiores, por exemplo, incluindo e excluindo diretórios (muito útil quando você for o Tutor). Então, recomendo que você faça o fork do repositório de grupo de estudos, crie um novo entroncamento/ramo com o nome da sua aula e nele adicione seu diretório com os seus arquivos. Faça então um pull-request.


### Manipualção de Diretórios
Demonstração na prática, no encontro. As anotações virão posteriormente para cá.

### Markdown
  + [RMarkDown.pdf](https://github.com/gabano/studyGroup/files/11768/rmarkdown-cheatsheet.pdf)
