# Check-Point 03 - Flexbox & Transformações 🍷💡

## Estrutura do Projeto
```bash
checkpoint03-flexbox/
├── index.html
├── README.md
└── css/
    └── flex-style.css
```

## Nome do Projeto
Vinheria Agnello — Plataforma Institucional com Monitoramento Automatizado de Adega

## Descrição do Projeto
Evolução técnica da interface web da Vinheria Agnello desenvolvida pelo grupo **MIXTAPE**. Esta versão consolida o design dark/premium e as transições fluídas desenvolvidas no CP2, adaptando a estrutura para o modelo de caixas flexíveis (CSS Flexbox) e adicionando transformações táteis para atender aos critérios exigidos no CP3.

---

## 📊 Matriz de Recursos Aplicados (CP3)

| Componente da Página | Propriedade Flexbox Aplicada | Pseudo-classes Utilizadas | Transformações CSS3 |
| :--- | :--- | :--- | :--- |
| **Menu Superior (`.main-header`)** | `display: flex; justify-content: space-between; align-items: center;` | `:hover` (Foco cromático)<br>`:focus` (Acessibilidade técnica) | `transform: scale(1.05);` (Ampliação sutil do link ativo) |
| **Banner Principal (`.hero-banner`)** | `display: flex; justify-content: center; align-items: center;` | `:hover` (Interação no botão) | `transform: translateY(-2px);` (Elevação fluida do botão principal) |
| **Grade de História (`.cards-container`)** | `display: flex; justify-content: center; gap: 40px; flex-wrap: wrap;` | `:hover` (Destaque tridimensional)<br>`:nth-child(odd/even)` (Bordas alternadas) | `transform: scale(1.02);` (Aumento progressivo de tamanho do card) |
| **Adega Inteligente (`.tech-wrapper`)** | `display: flex; align-items: center; gap: 60px; flex-wrap: wrap;` | `:hover` (Feedback visual na imagem) | `transform: rotate(0.5deg) scale(1.01);` (Leve rotação da área de hardware) |
| **Formulário de Contato (`.contact-form`)** | `display: flex; flex-direction: column;` | `:focus` (Suavização e brilho no campo selecionado) | `transform: translateY(-3px);` (Elevação tátil do botão de envio) |

---

## 👤 Desenvolvedor
- **Nome Completo1:** Gabriel Souza Bore de Carvalho
- **Nome Completo2:** rafael de oliveira santos zuccon

- **Instituição:** FIAP Paulista
- **Grupo Original:** MIXTAPE

## Links do Projeto
- **Repositório GitHub:** [(https://github.com/mixtapegbl/CP3-Vinheria)]
- **GitHub Pages:** [(https://vinheria-rustica-adega-agnello.netlify.app)]
