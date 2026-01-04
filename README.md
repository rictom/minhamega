# MINHAMEGA
Simulador de sorteio da Megasena utilizando a biblioteca matter.js. O projeto roda no navegador, basta abrir o arquivo index.html com a pasta static que contém as imagens e o áudio.<br>

## Versão Online:
[MinhaMega](https://minhamega.pythonanywhere.com) rodando no pythonanwhere.com.

## Observações:
O grosso do código foi gerado pelo Google Gemini. A idéia do projeto foi inspirado em https://github.com/hxrshdeepsingh/HTML5-Lottery-Game.<br>
As bolas selecionadas serão as que estiverem na parte inferior do globo.<br>
Não há uma boa detecção de colisão, por isso de vez em quando as bolas saem do globo. As bolas que escapam são reinseridas depois de alguns segundos.<br>
O parâmetro de elasticidade muito alto faz o sistema ficar instável. Se isso acontecer, pressione o botão Reiniciar.<br>
A biblioteca matter.js é 2D, por isso não espere um resultado realista! 
