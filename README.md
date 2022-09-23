# SOBRE PADROES DE PROJETO

Padrões de projeto são soluções consolidadas para problemas recorrentes no desenvolvimento e manutenção de software orientado a objetos.
O livro Design Patterns: Elements of Reusable Object-Oriented Software (1995) é a principal referência sobre o tema, a qual tornou os autores "Gamma, Helm, Johnson e Vlissides" conhecidos como Gang of Four (GoF).

São classificados nas seguintes categorias:<br>
* Padrões criacionais: Abstract Factory, Builder, Factory Method, Prototype, Singleton.<br>
* Padrões comportamentais: Chain of Responsibility, Iterator, Obeserver, Strategy, Template Method.<br>
* Padrões Estruturais: Adapter, Bridge, Composito, Decorator, Facade, Flyweight, Proxy.<br>

## Estrutura de projetos que iremos abordar

* Singleton: Permite a criação de uma única instância de uma classe e fornece um modo para recuperá-la.
![image](https://user-images.githubusercontent.com/73142478/192041323-d9955838-c86f-4b9b-8651-8bac93a0f7da.png)

* Strategy: Simplifica a variação de algoritmos para a resolução de um mesmo problema.
![image](https://user-images.githubusercontent.com/73142478/192041049-2ac2f78e-4477-41f9-bb94-8a5921e5bbe9.png)

* Facade: Prover uma interface que reduza a complexidade nas integrações com subsistemas.
![image](https://user-images.githubusercontent.com/73142478/192041702-6244e296-e8c1-4274-b38c-a52142f2ed7f.png)

# SOBRE A API 

### A intenção é explorar padrões de projetos criando uma API REST com os métodos CRUD.

## Tecnologias utilizadas 
* SpringBoot utilizando as dependências SpringWeb, SpringJPA, OpenAPI, H2 para armazenamento em memória
* IDE Eclipse e todo código em JAVA 

## END POINTS

### POST
* Inserimos um nome e CEP e API nos retorna o endereço completo 
![image](https://user-images.githubusercontent.com/73142478/192067268-c420a593-b7a4-4471-a93e-6655578b8c89.png)
![image](https://user-images.githubusercontent.com/73142478/192067544-d6323daf-c9d5-4b0c-aff6-8bcd171712d3.png)

### PUT
* Mudamos de CEP para atualizar o cliente
![image](https://user-images.githubusercontent.com/73142478/192069779-cb155b81-28b1-4962-9393-b25c16601c04.png)
![image](https://user-images.githubusercontent.com/73142478/192069804-08cfad2d-b1bd-4a5e-ae35-ea2a69b9b4fa.png)

### GET
* Listamos o cliente criado e atualizado
![image](https://user-images.githubusercontent.com/73142478/192069923-257227cb-91eb-410b-bac2-646e4a2132c5.png)

### DELETE
* Excluímos o cliente criado
![image](https://user-images.githubusercontent.com/73142478/192070063-b18baf68-df80-4410-8990-57a89f0faa2d.png)
![image](https://user-images.githubusercontent.com/73142478/192070144-fb0bc886-48ac-4e44-a7b2-b4be6b3999b6.png)
