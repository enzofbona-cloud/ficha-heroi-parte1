# Ficha de Herói — The Knight (Parte 1)

Projeto prático (HTML + CSS): ficha de RPG em página web.

**Personagem:** The Knight, o Cavaleiro do Vazio. Nascido no Abismo, é um receptáculo silencioso e determinado que enfrenta a infecção de Hallownest com seu ferrão. Personagem inspirado em *Hollow Knight* (Team Cherry).

- **Protótipo:** [COLE AQUI O LINK DO SEU PROTÓTIPO]
- **Repositório:** https://github.com/enzofbona-cloud/ficha-heroi-parte1

## Estrutura
```
ficha-heroi-parte1/
├── index.html
├── style.css
├── README.md
└── imagens/
```
Para abrir: dê duplo clique em `index.html` (ou use a extensão Live Server do VS Code).

## Requisitos aplicados
- 4 seções: Sobre o Herói, Atributos & Habilidades, Inventário & Conquistas, Contato com a Guilda.
- HTML semântico: `header`, `nav`, `main`, `section`, `article`, `footer`, `h1`/`h2`/`h3`, imagens com `alt` descritivo.
- Flexbox no menu; CSS Grid no inventário (1 coluna no celular, 2 no tablet, 3 no desktop).
- Variáveis CSS em `:root` (paleta do Vazio), barras de atributo com `div` e `width` em %, `transition` nos cards e no botão, pseudo-elementos `::before`, CSS em blocos comentados.
- Item de destaque com raridade (Ferrão, lendário) e raridades nos amuletos (comum, raro).

## Decisões de UI/UX
- **Hierarquia visual:** o nome "The Knight" é o maior texto da página (fonte serifada, até 5rem), ao lado do avatar. Em seguida vêm os títulos de seção, e por fim os atributos.
- **Contraste e legibilidade:** texto claro (`#eef1fa`) sobre fundo quase preto, e texto secundário (`#aab5d6`) com contraste acima de 4,5:1 (WCAG AA).
- **Consistência:** todos os cards usam a mesma borda, o mesmo raio e o mesmo espaçamento, e todas as barras de atributo repetem o mesmo padrão.
- **Proximidade e agrupamento (Gestalt):** nome do atributo, valor e barra ficam juntos, e os atributos são divididos em três grupos com título.
- **Lei de Fitts e affordance:** links do menu e botão têm no mínimo 44 px de altura; hover e foco mudam cor e tamanho, sinalizando que são clicáveis.
- **Fluxo de leitura:** a página segue um percurso natural de cima para baixo: quem é o herói → o que ele faz → o que ele carrega → como falar com a guilda.
