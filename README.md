> O repositório oficial está na conta da Mariah-Gomes; eu apenas o repostei na minha também.

# Jogo de Memorização

> Status do Projeto: Finalizado

> Observação: Esse projeto nos foi proposto no 4ºSemestre na disciplina de Arquitetura de Computadores

> Esse projeto fizemos presencialmente juntos, porém, muitas vezes subindo para o GitHub em apenas uma máquina

### Tópicos
🔹[Descrição do Projeto](#pencil-descrição-do-projeto)

🔹[Funcionalidade](#mag_right-funcionalidade)

🔹[Tecnologias Utilizadas](#computer-tecnologias-utilizadas)

🔹[Desenvolvedores](#busts_in_silhouette-desenvolvedores)

## :pencil: Descrição do Projeto

<div align="justify">
	
Neste projeto, decidimos realizar um jogo em Assembly onde o usuário possa visualizar no display uma sequência de números, que ficam um tempo no display e o usuário terá que decorar a sequência dos números e em seguida digitar a sequência utilizando comunicação serial do EdSim 51. 
	
Caso, o usuário esteja correto ele sobe de nível, ou seja, mostra um array diferente para o usuário. Portanto, o jogo terá 4 níveis diferentes, entre eles, o fácil com 4 números, o médio com 6 números, o díficil com 8 números e um GOD (super díficil) com 10 números. Caso, o usuário errar a sequência o jogo termina e ele terá que recomeçar. Mas, se o jogador ganhar, mostra uma mensagem na tela de comemoração, o jogo finaliza e volta para o início. Onde o usuário precisa digitar 1 para recomeçar o jogo. 	

</div>

## :mag_right: Funcionalidade
1. Para iniciar o jogo o usuário precisa digitar na comunicação serial do EdSim 51 o número 1.
   
<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/5a8a35b6-d47e-4a52-9e22-dfcb11d7e1dd"/>
</div>

2. Após o EdSim 51 receber o número 1 mostra a tela de início do jogo e o jogo começa a rodar. 

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/efc76219-2780-4e4e-9862-1094d848f83c"/>
</div>

3. O primeiro nível do jogo é o nível fácil com 4 números. Portanto, no jogo mostra no display qual é o nível que o usuário está jogando, e a sequência dos números. Depois de um tempo para o usuário memorizar aparece no display uma mensagem dizendo que o usuário pode digitar os números e enviar eles através do comunicador serial do EdSim 51. Além disso, se o usuário digitar menos números que o previsto do nível ou digitar mais números ele perde e o jogo reinicia.  Em particular, demostramos apenas as fotos do nível fácil, porém, esse procedimento acontece nos outros níveis da mesma forma, mas, no final do último nível mostra uma mensagem de parabéns e o jogo reinicia.

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/bfd04a03-b8fe-4c30-8299-59765c742176"/>
</div>

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/2aaea003-79f6-498a-adb9-8231419e196d"/>
</div>

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/f175afe0-4b1a-4e8b-88b3-3473ccb26fc0"/>
</div>

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/4b20288e-a159-4621-9570-f06758316f29"/>
</div>

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/0f363ff9-038c-474b-9a65-970caf0218a0"/>
</div>

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/8a4c8edf-e8f3-44fd-9d4f-a7b4b06da800"/>
</div>

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/1fd8c7c5-9e71-48d4-a388-bb0682efa8d5"/>
</div>

<div align="center">
	<img src="https://github.com/Mariah-Gomes/ProjetoAssembly/assets/141663285/b4cb5325-dbae-414d-bca4-6bbb5250846d"/>
</div>

## :computer: Tecnologias Utilizadas
- Utilizamos o simulador para 8051 chamado EdSim 51;
- A linguagem que utilizamos foi Assembly;

## :busts_in_silhouette: Desenvolvedores
| [<img loading="lazy" src="https://github.com/Mariah-Gomes/ProjetoCompMovel1/assets/141663285/e6827fd1-d8fe-4740-b6fc-fbbfccd05752" width=115><br><sub>Mariah Santos Gomes</sub>](https://github.com/Mariah-Gomes) | [<img loading="lazy" src="https://github.com/Mariah-Gomes/ProjetoCompMovel1/assets/141663285/66d7e656-b9e4-43b7-94fa-931b736df881" width=115><br><sub>Iago Rosa de Oliveira</sub>](https://github.com/iagorosa28) |
| :---: | :---: |
