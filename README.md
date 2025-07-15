# ✨ Minha Identidade Visual

---

## 🧠 Sobre

Minha identidade visual é um equilíbrio entre seriedade e modernidade. Uso cores neutras como bege, branco e cinza para transmitir calma e profissionalismo, mas sem perder o toque de personalidade com roxo vibrante e verde menta, que trazem frescor e originalidade.

A tipografia é limpa e acessível, com fontes **sans-serif** que garantem clareza e facilidade de leitura, mostrando que meu projeto é confiável, contemporâneo e pensado pra ser fácil de usar.

---

## 🎨 Paleta de Cores

### Cores principais

- **Roxo (cor primária):** `#9933CC`
- **Verde menta:** `#66CC99`
- **Laranja claro:** `#FFCC66`
- **Azul médio:** `#336699`
- **Cinza escuro:** `#333333`
- **Bege claro:** `#F2F2F2`

### Cores secundárias

- **Branco:** `#FFFFFF`
- **Cinza Claro:** `#CCCCCC`
- **Azul Claro:** `#6699CC`
- **Amarelo Claro:** `#FFCC00`
- **Cinza Médio:** `#666666`

### 🌈 Escala de cores (tons adicionais)

```css
// Roxo
--roxo-100: #e6ccf5;
--roxo-500: #9933cc;
--roxo-900: #4d1966;

// Verde Menta
--menta-100: #ccf2e2;
--menta-500: #66cc99;
--menta-900: #2f5f47;

// Amarelo Pastel
--amarelo-100: #fff3cc;
--amarelo-500: #ffcc66;
--amarelo-900: #996600;

// Azul Médio
--azul-100: #cce0f2;
--azul-500: #336699;
--azul-900: #1a334d;

// Neutros
--cinza-100: #f2f2f2;
--cinza-500: #999999;
--cinza-900: #333333;
```

---

## 🔠 Tipografia

### Fonte principal: **Montserrat**
- Usada para títulos e destaques
- Moderna, geométrica, com presença visual
- Peso: `semibold` a `bold`
- Tamanhos:  
  - H1: `32px`  
  - H2: `24px`
- Letter-spacing: `+0.5px`

### Fonte secundária: **Open Sans**
- Ideal para textos longos
- Leve, legível, confortável
- Tamanho: `16–18px`
- Peso: `regular`
- Line-height: `1.5`

### Fonte alternativa (opcional): **Poppins**
- Ótima para CTAs, botões e subtítulos
- Visual jovem e amigável
- Peso médio, espaçamento padrão

**Obs:** Todas as fontes são _sans-serif_.

---

## 🧩 Ícones

- Estilo: **outline**, visual limpo
- Bordas arredondadas (visual amigável)
- Tamanho ideal: `16×16px` ou `24×24px`
- Stroke: `2px`
- Famílias recomendadas: **Feather**, **Lucide**, **Heroicons**

---

## 📦 Elementos Visuais e Estilo

### Botões
- Bordas arredondadas (`6–8px`)
- Sombra leve
- Transições suaves

### Layout
- Estilo flat
- Sem texturas
- Clean e funcional

### Formas
- Geométricas suaves
- Cantos levemente arredondados

### Espaçamento
- Generoso
- Layout arejado

---

## 📐 Layout e Grid

- Grid: `12 colunas`
- Responsividade: `100%`
- Margens: amplas
- Headers: fixos, destaque em roxo ou azul escuro
- Footers: cinza médio sobre fundo branco

---

## 🌞 Light Mode

- Fundo geral: `#F2F2F2`
- Seções/base: `#FFFFFF`
- Texto principal: `#333333`
- Texto secundário: `#666666`
- Destaques: `#9933CC`, `#66CC99`, `#6699CC`
- Botões/Alertas: `#FFCC66`, `#FFCC00`

---

## 🌚 Dark Mode

- Fundo geral: `#121212`
- Seções/cards: `#1E1E1E`
- Texto principal: `#FFFFFF`
- Texto secundário: `#CCCCCC`
- Destaques: `#9933CC`, `#66CC99`, `#6699CC`
- Botões/Alertas: `#FFCC66`, `#FFCC00`

---

## 🖱️ Estados de Interação

### Botões

| Estado   | Estilo |
|----------|--------|
| Default  | `bg-roxo-500 text-white` |
| Hover    | `bg-roxo-900 shadow-md` |
| Focus    | `outline outline-2 outline-roxo-100` |
| Disabled | `bg-cinza-100 text-cinza-500 cursor-not-allowed` |
| Pressed  | `scale-95 shadow-inner` |

### Inputs

| Estado   | Estilo |
|----------|--------|
| Default  | `border border-cinza-500` |
| Focus    | `border-roxo-500 ring-1 ring-roxo-100` |
| Error    | `border-red-500 bg-red-50` |
| Disabled | `bg-cinza-100 text-cinza-500` |

---

## ♿️ Acessibilidade Visual

- Contraste mínimo: **nível AA**
- Foco visível em todos os elementos interativos
- Ícones com `aria-label` ou `title`
- Informações importantes nunca são transmitidas só por cor

---

## 🌀 Motion & Microinterações

- **Botão clicado:** `scale(0.95)` com `ease-in-out 150ms`
- **Cards aparecendo:** `fadeIn + translateY(10px)`
- **Modais/popovers:** `fade + scale(0.95 → 1.0)`
- **Toast:** `slide-in-right` com bounce sutil

```css
transition: all 200ms cubic-bezier(0.4, 0, 0.2, 1);
```

---

## 🗣️ Tom de Voz e Personalidade Escrita

### Estilo: Profissional com leveza e humanidade

A ideia é comunicar com simpatia e acessibilidade, sem perder a credibilidade. Misturo um tom sério com aquele jeitinho próximo de quem quer ajudar e deixar a experiência leve.

### Frases padrão

- **Erro:** “Opa! Algo deu errado, mas já estamos de olho nisso.”
- **Sucesso:** “Tudo certo! Sua tarefa foi concluída com sucesso 👌”
- **Carregando:** “Só um segundinho enquanto preparamos tudo pra você…”

### Palavras-chave

> Confiável, leve, acessível, ágil, moderna, companheira

### Esse README aqui é o mapa da minha identidade visual, todo pensado e feito na humildade pra mostrar quem eu sou no projeto. Se quiser trocar ideia, dar um toque ou até colaborar, só chegar! Tamo junto.
