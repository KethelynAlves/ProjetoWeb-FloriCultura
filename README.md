# 🌸 FloriCultura - E-commerce & Ateliê Floral

✨ **FloriCultura** é uma plataforma web para uma floricultura e café. O projeto conta com catálogo dinâmico de flores, cálculo em tempo real de encomendas, formulários com validações customizadas e um mecanismo de busca textual interno.

---

### ✨ Funcionalidades
- **🌾 Glossário de Flores Dinâmico:** Carregamento de tabela de flores e preços consumidos via API Fetch de um arquivo `JSON`.
- **🛒 Formulário de Encomendas Dinâmico:** 
  - Seleção de produtos prontos (arranjos e cestas) e/ou flores avulsas.
  - Cálculo automático do valor total do pedido com ajuste por quantidade e multiplicadores de tamanho.
  - Formatação interativa da máscara do campo de celular `(XX) XXXXX-XXXX`.
  - Validações completas de data (bloqueando datas passadas), horário, e-mail e campos obrigatórios.
- **🔍 Mecanismo de Busca Interna:** Realce dinâmico (*highlight*) e rolagem suave até o termo pesquisado na página.
- **🎥 Galeria Multimídia:** Exibição de produtos com suporte a imagens e vídeos demonstrativos integrados.
- **💌 Formulário de Contato:** Comunicação com validação client-side.

---

### 🛠️ Tecnologias e Ferramentas
- 🛠️ **HTML5:** Estruturação semântica de múltiplas páginas e formulários.
- 🛠️ **CSS3:** Estilização personalizada, paleta de cores em tons pastel e responsividade.
- 🛠️ **Bootstrap 5:** Sistema de grid, componentes de navegação (`Navbar`), carrossel (`Carousel`), formulários e áreas expansíveis (`Collapse`).
- 🛠️ **JavaScript (ES6+):** Manipulação da DOM, consumo de JSON assíncrono (`fetch`), Regex para máscaras/validações e cálculo dinâmico de valores.
- 🛠️ **JSON:** Armazenamento dos dados do catálogo de flores e preços.

---

### 📂 Estrutura do Projeto

```text
.
├── index.html            # Página principal (Home com carrossel e apresentação)
├── style.css             # Estilização global e componentes
├── scripts.js            # Lógica de validação, busca, cálculo de totais e Fetch JSON
├── tabela.json           # Dados das flores (Nome, definição e valor)
├── pages/
│   ├── Arranjos.html     # Catálogo de arranjos com vídeos e imagens
│   ├── Cestas.html       # Catálogo de cestas especiais
│   ├── TiposFlores.html  # Glossário com tabela populada via JSON
│   ├── Encomendas.html  # Formulário de pedido com cálculo dinâmico
│   └── Contato.html     # Formulário de atendimento e contatos
└── images/               # Imagens, logotipos e vídeos do projeto
