# 🏁 Corrida de Carros - Jogo em HTML e JavaScript

Um jogo de tabuleiro interativo com tema de corrida, feito em HTML, CSS e JavaScript. Quatro carros competem em uma pista com caminho em zigue-zague, movimentando-se com base em cartas aleatórias.

## 🎮 Como Jogar

1. **Escolha um carro** no seletor.
2. **Clique em uma carta** para selecioná-la.
3. Clique em **Mover** para avançar o carro selecionado com base no número da carta.
   - Apenas **a carta utilizada será atualizada** com um novo número aleatório.
4. O carro **não pode ultrapassar os limites** da pista:
   - Não pode ir abaixo da casa 0.
   - Não pode passar da casa final.
5. Quando um carro chegar à última casa, o jogo exibirá:
   > `Carro [COR] Venceu!`
6. Após a vitória, todos os botões permanecem visíveis, mas os movimentos são bloqueados.
7. Você pode clicar em **Reiniciar** a qualquer momento para:
   - Resetar a posição dos carros.
   - Gerar novas cartas.
   - Limpar a mensagem de vencedor.

## 🧱 Tecnologias Utilizadas

- HTML5
- CSS3 (tema escuro + responsividade)
- JavaScript puro (sem frameworks)

## 🖼️ Imagens

- As imagens dos carros são utilizadas como `background-image` nos quadrantes. 
- Os arquivos esperados são:
  - `car-blue.png`
  - `car-red.png`
  - `car-green.png`
  - `car-yellow.png`

Eles devem estar na **mesma pasta do arquivo HTML**.

## 🚀 Como Executar

1. Clone ou baixe este repositório.
2. Coloque as imagens dos carros na pasta do projeto.
3. Abra o arquivo `index.html` em um navegador moderno (Chrome, Firefox, Edge).

4. Ou acesse o link: https://wilsongsf.github.io/race-cars/

5. Divirta-se!

---

Criado por Wilson Gomes 🚗💨
