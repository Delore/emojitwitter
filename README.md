# EmojiTwitter

### O projeto consiste em criar um app que seja capaz de consumir apis do Twitter, para selecionar um tweet e analisar o sentimento do texto, apresentando um emoji feliz, neutro ou triste de acordo com o resultado da api do google de análise de linguagem natural.

## Resultado
### Neste projeto, foi demonstrado a capacidade do desenvolvedor criar um app funcional aplicando arquitetura e utilizando algumas das principais bibliotecas que fazem parte do Android Jetpack e do mercado.

## Principais habilidades demonstrado:
1. Consumo de APIs com Retrofit.
2. Autenticação oAuth 1.0.
3. Consumo de APIs do Twitter.
4. Consumo de APIs do Google Cloud Natural Language.
5. Downloads e cache de imagem utilizando Picasso.
6. Aplicação de arquitetura Clean Architecture com Android Architecture Components
7. Utilização do Dagger2 para inversão de dependencia.
8. Utilização de banco de dados SQLite para armazenar dados offline.
9. Utilização bibliotecas do Android Jetpack(Room, LiveDate, Navigation e LifeCycles).
10. Utilização de animações em Lottie.
11. Utilização do padrão MPV.
12. Criação de Listas utilizando ReclycleView com scroll infinito

## Descrição
### Camada de Dados:
* Foi aplicado o padrão MPV e Architecture para separar as responsabilidade de cada camada.
* Usando o Dagger foi possível separar as dependencia da camadas de dados com as outras camadas.
* Na camada de dados foi utilizado o Retrofit, simplesmente facilita muito as requisições de HTTPs, juntamente com o uso do Gson para serializar e desserializar os JSONs.
* Foi criado um padrão para criar as requisições e tratar os dados salvando em banco de dados todos os resultados para acesso quando o device estiver sem conexão com a internet.
* Para o banco de dados foi utilizado o Room.

### Camada de Dominio
* Apenas foi criado as entidades nesta camada.

### Camada de Apresentação
* Nesta camada foi utilizado o presenter e view para separar as responsabilidades.
* No presente foi utilizado o viewmodel do Jetpack, ele permite manter dados aprova do ciclo de vida do Android.
* Foi utilizado também o LiveDate para notificar as alterações de dados vindo das camadas anteriores.
* Com o LifeCycles, foi possível dar para o presenter a capacidade de observar o ciclo de vida da activity principal.
* Para navegação foi utilizado o Navigation que permitiu cria um navegação sem se preocupar com a pilha de fragments.
* Criando também algumas classes bases, para reaproveitar alguns recursos e evitar códigos duplicados.

# Vídeo
![Screenshot](youtube.jpg)(https://youtu.be/V70YzNiSvsw)

# Contato
### E-Mail: [delore23@mail.com](delore23@gmail.com)
