# 🐕 Pegue o Juquinha

Joguinho 2D em pixel art onde a personagem (Rhayssa) arremessa uma bolinha de tênis, o cachorro **Juquinha** corre buscar, e depois ela precisa correr atrás dele pra recuperar — dentro de 20 segundos e ainda coletando 2 bolinhas bônus pelo mapa.

## Como jogar

**Teclado (PC):**
- `Setas` ou `WASD` — mover a Rhayssa
- `Espaço` — arremessar a bolinha
- `Enter` — recomeçar após game over

**Touch (celular):**
- Joystick virtual no canto inferior esquerdo
- Botão 🎾 no canto inferior direito — arremessar
- Botão 🔄 no canto superior direito — reiniciar a qualquer momento

## Regras

1. Você começa com a bolinha azul. Arremessa em qualquer direção.
2. Assim que arremessa, **20 segundos** começam a contar, e duas bolinhas bônus (🔴 vermelha e 🟡 amarela) aparecem em locais aleatórios do mapa.
3. O Juquinha corre atrás da bolinha azul, pega e foge pelo mapa.
4. **Pra completar o round** você precisa:
   - Pegar a bolinha vermelha
   - Pegar a bolinha amarela
   - Encostar no Juquinha pra recuperar a bolinha azul
5. Se acabar o tempo, aparece **"Rhayssa cansou! 😴"** e o jogo reinicia.
6. Cuidado com o **buraco** no chão fora do quarto superior! 🕳️

## Tecnologia

HTML + Canvas + JavaScript puro, sem dependências. Sprites em pixel art com chroma key (fundo magenta → transparente).
