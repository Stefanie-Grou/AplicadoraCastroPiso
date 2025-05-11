# README - Aplicadora Castro Piso

## 📌 Visão Geral
Este projeto é o website de portfólio da **Aplicadora Castro Piso**, uma empresa especializada em serviços profissionais para pisos de madeira, incluindo restauração, instalação e tratamentos preventivos. O site apresenta:

- Seção hero com chamada principal
- Catálogo de serviços oferecidos
- Comparativo "antes/depois" de trabalhos realizados
- Galeria de imagens de projetos concluídos
- Informações de contato

## 🛠 Tecnologias Utilizadas
- **HTML5** - Estrutura semântica do conteúdo
- **CSS3** - Estilização responsiva sem frameworks
- **Design System**:
  - Cores terrosas (#6B4F3B, #2c1810, #f8f1e6)
  - Tipografia Arial
  - Cards com efeitos hover
  - Layout em grid

## 🎨 Estrutura do Projeto
```bash
├── index.html          # Página principal
├── assets/
│   ├── img/            # Imagens do portfólio (1.jpg, 2.jpg...)
│   │   ├── Instalação.png
│   │   ├── Trocas de peças.png
│   │   └── ...
└── README.md           # Este arquivo
```

## 🔍 Principais Componentes

### 1. Hero Section
- Banner principal com overlay escuro
- Título e subtítulo centralizados
- Imagem de fundo em full-width

### 2. Seção de Serviços
- Grid responsivo de cards (2 colunas em desktop)
- 8 serviços detalhados com:
  - Imagem ilustrativa
  - Título descritivo
  - Breve descrição

### 3. Comparação Antes/Depois
- Layout side-by-side
- Imagens circulares com legendas
- Fundo contrastante

### 4. Galeria
- Grid de 8 imagens de projetos
- Layout responsivo (4 colunas em desktop)

## 📱 Responsividade
O site utiliza:
- `viewport` meta tag
- Unidades relativas (rem, %)
- Grid CSS com `auto-fit` e `minmax()`
- Media queries implícitas

## 📄 Licença
© 2006-2025 Aplicadora Castro Piso - Todos os direitos reservados

> **Nota**: Este projeto é estático e não requer dependências externas ou processos de build. Para edições, modifique diretamente o arquivo HTML/CSS.
