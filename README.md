Projeto: Sistema de Gerenciamento de Funcionários
Descrição
Este projeto é um sistema de gerenciamento de funcionários para uma indústria. Ele permite inserir, remover, listar e manipular informações dos funcionários, bem como agrupar e filtrar essas informações de diversas formas.

Requisitos
O projeto deve atender aos seguintes requisitos:

Classe Pessoa com os atributos:

nome (String)
dataNascimento (LocalDate)
Classe Funcionário que estenda a classe Pessoa, com os atributos:

salário (BigDecimal)
função (String)
Classe Principal para executar as seguintes ações:

3.1 Inserir todos os funcionários, na mesma ordem e informações da tabela fornecida.
3.2 Remover o funcionário "João" da lista.
3.3 Imprimir todos os funcionários com todas suas informações, formatando a data no formato dd/MM/yyyy e o salário com separador de milhar como ponto e decimal como vírgula.
3.4 Atualizar a lista de funcionários com um aumento de 10% no salário.
3.5 Agrupar os funcionários por função em um Map, sendo a chave a função e o valor a lista de funcionários.
3.6 Imprimir os funcionários agrupados por função.
3.8 Imprimir os funcionários que fazem aniversário nos meses de outubro (10) e dezembro (12).
3.9 Imprimir o funcionário com a maior idade, exibindo os atributos: nome e idade.
3.10 Imprimir a lista de funcionários em ordem alfabética.
3.11 Imprimir o total dos salários dos funcionários.
3.12 Imprimir quantos salários mínimos ganha cada funcionário, considerando que o salário mínimo é R$1212.00.
Estrutura do Projeto
O projeto está organizado da seguinte forma:

src/: Contém os arquivos fonte do projeto.
model/: Contém as classes de modelo (Pessoa e Funcionario).
util/: Contém classes utilitárias, se necessário.
Main.java: Contém a classe principal que executa as ações requeridas.
Dependências
Para rodar este projeto, você precisa do seguinte:

JDK 8 ou superior
IDE de sua escolha (Eclipse, NetBeans, IntelliJ, etc.)
Instruções para Execução
Clone o repositório:

sh
Copiar código
git clone <link-do-repositorio>
cd <nome-do-diretorio>
Importe o projeto em sua IDE:

Abra sua IDE de escolha.
Importe o projeto como um projeto Maven existente (se aplicável).
Execute a classe principal:

Localize a classe Main.java no pacote src/.
Execute a classe Main como uma aplicação Java.
Considerações Finais
Este projeto foi desenvolvido para demonstrar conhecimentos em Java, incluindo manipulação de datas, formatação de saída, e uso de coleções. Comentários foram adicionados ao código para explicar partes complexas ou decisões de design.

Caso haja alguma funcionalidade que não foi desenvolvida, isso será indicado através de comentários no código, juntamente com uma explicação do motivo.

Contato
Para mais informações, dúvidas ou sugestões, entre em contato através do e-mail: [kenedytere@gmail.com]
