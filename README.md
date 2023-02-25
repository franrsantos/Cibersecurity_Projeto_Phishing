# Cibersecurity_Projeto_Phishing
Criando um Phishing no Kali Linux - Formação Cybersecurity Specialist - DIO

Primeiramente entrar como Root:

`Sudo su`

informar a senha.

Acessar o Setoolkit utilizando:

`Setoolkit`

No menu de opções selecionar o tipo de ataque, será utilizado o módulo de Engenharia Social, digitando `Nº 1 (enter)`. 
Após isso ele apresenta uma lista de vetores de ataques, vamos utilizar o `Nº 2 [ Websites Attack Vectors ]`.

Na próxima tela ele mostra a explicação de tipos de ataques que ele utiliza.

Neste caso vamos utilizar a `Nº 3  [ Credential Harvester Attack Method ]`.
A seguir `Nº 2 [ Site Cloner ]`.


A seguir ele solicita algumas informações pois estamos rodando um pequeno servidor com uma página falsa, 
para isso ele precisa do IP da máquina, por isso é importante a máquina estar no modo Bridge para que possamos acessar ela de outras máquinas. 
Como ele já sugere este IP, podemos seguir com o processo clicando `enter`.
Após isso vamos informar a URL a ser clonada `http://facebook.com`. Para que ele crie a estrutura para que a gente consiga acessar.


Para acessar a página Fake criada, necessário copiar o Endereço IP `192.168.0.14`.

Ao observar o Kali ele mostra que tem alguém tentando acessar a página.
Ao tentar acessar a conta, ele tenta direcionar para a conta oficial do facebook, mas se você observar no Kali, ele mostra os dados coletados.

