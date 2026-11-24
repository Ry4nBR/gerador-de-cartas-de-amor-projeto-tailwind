# 💌 Gerador de Cartas de Amor (Escriba Inteligente)

> Aplicação web interativa para geração, personalização e exportação em PDF de cartas de amor apaixonadas, desenvolvida com **Tailwind CSS** e **Inteligência Artificial Nativa**.

---

## 👤 Autor
* **Desenvolvedor:** Ryan Amorim Carvalho  
* **Tema da Aplicação:** Gerador de Cartas de Amor  
* **Paleta de Cores:** Cores Quentes — Vermelho Carmim (`#4c0519`, `#991b1b`), Ouro Metálico (`#f59e0b`, `#d97706`), Off-White Pergaminho (`#fcf8f2`) e Branco Puro (`#ffffff`).

---

## 💻 Sobre o Projeto

O **Gerador de Cartas de Amor** é uma plataforma que permite a qualquer pessoa criar uma declaração de amor personalizada, poética e emocionante em poucos passos. O sistema realiza uma entrevista guiada com o declarante, abordando memórias, sentimentos de proximidade e distância, promessas de futuro e momentos marcantes. 

A aplicação conecta-se de forma nativa a modelos de Inteligência Artificial para tecer as respostas da entrevista em uma carta coesa e poética. O resultado pode ser editado diretamente na folha de papel, estilizado em 4 modelos visuais e baixado em formato PDF.

---

## ✨ Principais Funcionalidades

1. **Entrevista Guiada com o Declarante:**
   - Perguntas sobre a pessoa amada, tom da mensagem, como se conheceram, pensamentos, memórias felizes e promessas.
2. **Geração Automática por IA (Gemini API):**
   - Criação instantânea do texto da carta a partir do preenchimento da entrevista.
   - **Refinamento em 1 clique:** Botões para ajustar o estilo da carta (*✨ Mais Poética*, *🔥 Mais Intensa*, *📜 Mais Curta* e *🖋️ Polir Gramática*).
3. **4 Modelos Visuais de Carta:**
   - **Clássico Real:** Estilo pergaminho histórico, borda dupla em ouro, selo de cera vermelho e letra capitular.
   - **Paixão Carmim:** Estilo contemporâneo com cabeçalho vinho profundo e ornamentos dourados.
   - **Minimalista Dourado:** Visual limpo em fundo neutro com detalhes estelares delicados.
   - **Poético & Floral:** Estilo delicado em rosa suave com tipografia itálica e ornamentação floral.
4. **Edição Direta no Papel:**
   - O corpo da carta possui o atributo `contenteditable="true"`, permitindo alterações manuais em tempo real.
5. **Exportação Profissional:**
   - Download da carta em PDF mantendo alta fidelidade visual via biblioteca `html2pdf.js`.
   - Cópia do texto formatado com um único clique.
6. **Interface Totalmente Responsiva:**
   - Adaptação perfeita para dispositivos móveis, tablets e desktops.

---

## 📸 Demonstração do Projeto (Screenshots)

*Inclua aqui os prints solicitados pela atividade na versão final do seu repositório:*

| Código da Aplicação | Interface em Funcionamento |
| :---: | :---: |
| ![Print do Código](./prints/codigo.png) | ![Print da Aplicação](./prints/aplicacao.png) |

| Modelo Clássico (PDF) | Entrevista Guiada |
| :---: | :---: |
| ![Print do PDF](./prints/pdf.png) | ![Print da Entrevista](./prints/entrevista.png) |

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica da página.
* **Tailwind CSS:** Estilização utilitária responsiva e estilização temática avançada.
* **JavaScript (ES6+):** Manipulação de DOM, integração com API de IA e controle dos modelos.
* **Google Fonts:** Fontes *Cormorant Garamond*, *Playfair Display*, *Plus Jakarta Sans* e *Dancing Script*.
* **Font Awesome:** Ícones vetoriais.
* **html2pdf.js:** Geração e renderização de arquivos PDF no navegador.

---

## 🎨 Tabela de Classes Tailwind CSS Utilizadas (+40 Classes)

Conforme os requisitos da atividade acadêmica, a tabela abaixo documenta mais de 30 classes do **Tailwind CSS** utilizadas no projeto com suas respectivas funções:

| Categoria | Classe Tailwind | Função e Aplicação no Código |
| :--- | :--- | :--- |
| **Cores de Fundo** | `bg-rose-950` | Define o fundo vinho escuro no cabeçalho e rodapé. |
| **Cores de Fundo** | `bg-rose-900` | Fundo carmim profundo para botões de ação e destaques. |
| **Cores de Fundo** | `bg-amber-500` | Cor de destaque em tom ouro metálico para ícones e badges. |
| **Cores de Fundo** | `bg-amber-50` | Fundo tom off-white levemente amarelado nos cards selecionados. |
| **Cores de Fundo** | `bg-stone-100` | Fundo principal da aplicação (tom neutro e acolhedor). |
| **Cores de Fundo** | `bg-white` | Fundo limpo dos cartões de formulário e modal. |
| **Cores de Texto** | `text-amber-100` | Cor do texto dourado claro em fundos escuros. |
| **Cores de Texto** | `text-rose-950` | Cor carmim escura para títulos de formulários e cabeçalhos da carta. |
| **Cores de Texto** | `text-stone-800` | Cor padrão para o corpo da carta, garantindo ótima legibilidade. |
| **Cores de Texto** | `text-transparent` | Torna o texto transparente para aplicação de gradientes. |
| **Gradientes** | `bg-gradient-to-r` | Aplica gradiente linear da esquerda para a direita em botões. |
| **Gradientes** | `bg-clip-text` | Recorta o gradiente de fundo no formato do texto do título. |
| **Tipografia** | `font-serif` | Aplica a família tipográfica serifada elegante para estilo literário. |
| **Tipografia** | `font-sans` | Aplica a família tipográfica limpa para elementos de interface. |
| **Tipografia** | `font-handwriting` | Fonte caligráfica manuscrita para a assinatura da carta. |
| **Tipografia** | `text-xs / text-sm / text-base` | Escala de tamanho dos textos explicativos, rótulos e corpo da carta. |
| **Tipografia** | `text-2xl / text-4xl / text-5xl` | Escala de títulos principais e cabeçalhos em destaque. |
| **Tipografia** | `font-bold / font-semibold` | Define a intensidade do peso da fonte nos elementos. |
| **Tipografia** | `italic` | Aplica estilo itálico poético na carta e notas de ajuda. |
| **Tipografia** | `tracking-widest` | Aumenta o espaçamento entre letras em legendas em caixa alta. |
| **Tipografia** | `leading-relaxed` | Define um espaçamento entrelinhas confortável para leitura. |
| **Espaçamentos** | `p-3 / p-5 / p-8 / p-12` | Preenchimento interno em múltiplos níveis (Padding). |
| **Espaçamentos** | `px-4 / py-2 / py-3.5` | Preenchimentos horizontais e verticais padronizados em botões. |
| **Espaçamentos** | `space-y-3 / space-y-4 / space-y-6` | Espaçamento vertical automático entre elementos filhos. |
| **Espaçamentos** | `gap-3 / gap-8` | Espaçamento interno entre itens de containers Flex e Grid. |
| **Dimensões** | `w-full / max-w-4xl / max-w-7xl` | Define larguras operacionais e limites para responsividade. |
| **Dimensões** | `min-h-screen / min-h-[650px]` | Define a altura mínima da janela e da folha da carta. |
| **Bordas** | `border / border-2 / border-4` | Define as espessuras das bordas visuais dos cards e folhas. |
| **Bordas** | `border-amber-400 / border-rose-200` | Cores ornamentais douradas e carmim para os contornos. |
| **Bordas** | `rounded-xl / rounded-2xl / rounded-full` | Arredondamento suave de cantos e elementos circulares. |
| **Sombras** | `shadow-md / shadow-xl / shadow-2xl` | Aplica sombras de profundidade em cartões e na folha da carta. |
| **Sombras** | `ring-2 / ring-amber-400/30` | Efeito de anel fluorescente ao selecionar o modelo ativo. |
| **Flexbox** | `flex / flex-col / flex-wrap` | Habilita o modelo Flexbox e define a orientação e quebra dos itens. |
| **Flexbox** | `items-center / justify-between` | Alinhamento vertical e distribuição dos elementos no espaço flex. |
| **Grid** | `grid / grid-cols-1 / grid-cols-2` | Define a malha responsiva para o formulário e opções. |
| **Grid** | `lg:grid-cols-12` | Malha de 12 colunas no breakpoint desktop (`lg`). |
| **Posicionamento** | `relative / absolute / fixed / sticky` | Define os modos de posicionamento espacial na tela. |
| **Posicionamento** | `top-0 / inset-0 / z-10 / z-30 / z-50` | Define a fixação e as camadas verticais (z-index) dos modais. |
| **Responsividade**| `sm: / md: / lg:` | Breakpoints adaptativos mobile-first. |
| **Interatividade**| `hover:bg-amber-400 / transition-all` | Transições suaves e efeitos ao passar o mouse. |
| **Efeitos** | `backdrop-blur-md / animate-pulse` | Desfoque de fundo em cabeçalhos e animação pulsante. |

---

## 🚀 Como Executar o Projeto Localmente

1. Clone o repositório ou faça o download dos arquivos:
   ```bash
   git clone https://github.com/seu-usuario/gerador-cartas-de-amor.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd gerador-cartas-de-amor
   ```
3. Abra o arquivo `index.html` em qualquer navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge ou Safari). Não é necessário instalar dependências nem servidores Node.js.

---

## 📜 Licença e Créditos

Desenvolvido por **Ryan Amorim Carvalho** como parte do projeto prático de desenvolvimento web e estilização avançada com **Tailwind CSS**.

*Sinta-se à vontade para contribuir, enviar feedback ou utilizar este gerador para espalhar o amor!* 💖