# The World Map
@ Projeto realizado para processo seletivo  

[![Image!](https://user-images.githubusercontent.com/25700237/116011049-4c459380-a5f9-11eb-8aba-98caa7e9a0f7.png)](https://www.youtube.com/watch?v=2h0RhhukLWI)  
on Youtube (v1.0)(https://www.youtube.com/watch?v=2h0RhhukLWI)

* Listagem de todos países.
* Pesquisa por nome.
* Localização por obtenção de ip ( Clique no botão com o campo de texto vazio ).


# Atualizações
OBS:(deve haver uma interface entre o navegador e projeto -> liveserver.Visual Studio Code)

* Adicionado uma função para alterar a forma como os dados do país selecionado é obtido, Memória(preload) / Get: API.
  * Este causara problema quando diversas requisições eram feitas, gerando um delay pela api para uma resposta.
  * Caso a demora seja de +200ms, uma animação o alertará.
* Novas animações foram criadas para a espera de resposta da API, como obtenção de todos os países e país específico.
  * O mesmo sugere para a listagem de países. Caso a api não responda.
* Tratamento sobre entrada de dados, caso o nome não seja encontrado, uma imagem o alertará.
* Estrutura do código reorganizada, minimizando blocos repetitivos.
  * Separação de arquivos, cuja funcionalidade correnpondam entre os mesmos elementos.
* Correção em nomes de países cujo o símbolo " ' " fora encontrado.
* Adicionado texto para mostragem de espera pela api para obter IP regional. (" Getting local country ").
* Mudança na animação que correnponde ao país residido pelo usuário.
* Outras alterações minuciosas foram feitas para o correto funcionamento de todas funções.

# Imagens referentes a algunas alterações visuais

![timeout_a](https://user-images.githubusercontent.com/25700237/117083776-d5f11180-ad1b-11eb-8311-da710344b4bf.PNG)
![timeout_b](https://user-images.githubusercontent.com/25700237/117083777-d8536b80-ad1b-11eb-87ff-17276dd25ea8.PNG)
![load](https://user-images.githubusercontent.com/25700237/117083782-da1d2f00-ad1b-11eb-9ce6-df9c0f5f9b7a.PNG)
![preload](https://user-images.githubusercontent.com/25700237/117083783-db4e5c00-ad1b-11eb-8d6e-136870576323.PNG)
![boneco](https://user-images.githubusercontent.com/25700237/117083801-ea350e80-ad1b-11eb-8245-faf0c8921c51.PNG)

[![image](https://user-images.githubusercontent.com/25700237/117085767-0d15f180-ad21-11eb-96a2-8533f3179e75.png)](https://www.youtube.com/watch?v=YFdp4RJkwdQ)
on Youtube (v1.1)(https://www.youtube.com/watch?v=YFdp4RJkwdQ)

