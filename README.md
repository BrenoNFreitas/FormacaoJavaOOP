![image](https://github.com/BrenoNFreitas/FormacaoJavaOOP/assets/65196156/d565d05e-b54f-46ef-b406-cde0ac83d8d6)


# FormacaoJavaOOP
Projetos construidos durante a formação com quatro cursos da ALura sobre programação em Java com Orientação a Objetos

- Fundamentos da Linguagem
- Orientação a Objetos
- Boas Práticas
- Listas e Coleção de Dados
- consumir API HTTP Java

## `Projeto 1`: No primeiro projeto, foi proposto criar uma aplicação que simula o controle de uma conta bancária.
Na aplicação terá quatro opções de ações que poderá ser feita através da entrada do usuário. Ao consultar o saldo, novamente 
será mostrado na tela o saldo previamente definido. Ao escolher receber valor, o usuário digita o valor a ser recebido.
Na opção tranferir valor, o usuário também vai digitar o valor a ser retirado da conta, e esta operação só será realizada se o valor 
da transferencia dor menor ou igual ao valor total da conta, caso contrário aparecerá uma mensagem informando que a tranferência não foi realizada.

![exemplo1](https://github.com/BrenoNFreitas/FormacaoJavaOOP/assets/65196156/597af515-eb60-43a2-aeda-6bf678dab4a4)

## `Projeto 2`: No segundo projeto, foi proposto a construção  uma aplicação para cadastrar nossas músicas e podcasts preferidos, modelando as classes utilizando os conceitos de orientação a objetos: abstração, herança, encapsulamento e polimorfismo.
Para o projeto, foi criado uma classe Audio com seus atributos, utilizando encapsulamento, deixando os atributos privados e 
criando os getters e setters para acessar e modificar os atributos. foi criado dois métodos sem retorno que irão incrementar as variáveis. 
Foi criado também outras duas classes estendendo a classe Audio e a classe principal para instanciar o objeto e executar o projeto.
Foi criado também um loop para chamar os métodos curte e reproduz para simular um número grande de reproduções e curtidas. Se a música tiver 
mais de 2000 reproduções a classificação será 10 e para valores inferiores a classificação será 8. E se o podcast tiver mais de 500 curtidas 
a classificação será 10 e para valores inferiores, a classificação será 7. Por fim, foi criada a classe MusicasPreferidas com um método sem retorno o inclui, 
que vai receber a classe Audio como parâremtro que de acordo com a subclasse que será passada e suas rescpectivas classificações ele mostrará a mensagem na tela.

![exemplo2](https://github.com/BrenoNFreitas/FormacaoJavaOOP/assets/65196156/c441ae7c-660d-48f0-9a83-bd61f3810915)

## `Projeto 3`: No projeto 3 foi protosto criar uma aplicação que registra as atividade de um cartão de crédito.
Primeiro o usuário irá definir o limite do cartão, logo depois ele vai fazer uma descrição da compra que ele quer fazer como no exemplo a descrição foi "fone", 
depois o usuário vai informar o valor da compra. em seguida ele terá a opção de continuar ou sair, e quando ele sair, será mostrada todas as atividades 
no "cartão" e todas as compras na ordem do menor ao maior valor.

![image](https://github.com/BrenoNFreitas/FormacaoJavaOOP/assets/65196156/35001d74-ac00-475f-969d-c54f5f560627)

![exemplo3](https://github.com/BrenoNFreitas/FormacaoJavaOOP/assets/65196156/2d5f3536-8bc8-4b72-b7a6-312b110ab759)

## `Projeto 4`: No quarto e ultimo projeto desta formação, foi proposto uma aplicação para consultar um endereço a partir de um CEP e salvar as informações em um arquivo json.
Primeiro criamos uma classe 'Record' para representar o Endereço. Criamos também uma classe que vai consultar a API e resgatar o enderço a partir do CEP que o usuário 
vai digitar na aplicação. Criamos também outras duas classes, a principal que vai resgatar a entrada do usuário com o CEP, e outra para salvar esse endereço que a API
vai retornar e salvar em um arquivo .json


![exemplo4pt1](https://github.com/BrenoNFreitas/FormacaoJavaOOP/assets/65196156/59984b50-ca87-4659-8da1-a48704f26857)
![exemplo4pt2](https://github.com/BrenoNFreitas/FormacaoJavaOOP/assets/65196156/60861710-3fe5-4ffe-affd-8184aa586506)
