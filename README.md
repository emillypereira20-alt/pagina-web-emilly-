# 🗂 Organização do Site

O projeto foi estruturado para facilitar manutenção, escalabilidade e futuras implementações.

## Estrutura Geral

```text
ecoanimal/
│
├── index.html          # Página principal
├── style.css           # Estilos globais
├── README.md           # Documentação do projeto
│
└── images/
    ├── banner.jpg
    ├── fauna.jpg
    └── preservacao.jpg
```

---

## Estrutura da Página

### Header
Responsável pela navegação principal do site.

```text
Header
 ├── Logo EcoAnimal
 └── Menu
      ├── Início
      ├── Sobre
      ├── Ações
      ├── Impactos
      └── Contato
```

---

### Hero Section

Área de destaque da página.

```text
Hero
 ├── Título Principal
 ├── Descrição
 └── Botão "Saiba Mais"
```

---

### Sobre

Apresenta informações sobre sustentabilidade animal.

```text
Sobre
 ├── Imagem
 └── Texto Explicativo
```

---

### Ações Sustentáveis

Lista práticas que contribuem para a preservação animal.

```text
Ações
 ├── Preservação de Habitats
 ├── Proteção da Fauna
 └── Educação Ambiental
```

---

### Impactos Positivos

Exibe indicadores e estatísticas.

```text
Impactos
 ├── Biodiversidade
 ├── Espécies Protegidas
 └── Benefícios Futuros
```

---

### Galeria

Mostra imagens relacionadas à fauna e preservação.

```text
Galeria
 ├── Imagem 1
 ├── Imagem 2
 └── Imagem 3
```

---

### Contato

Formulário para interação com usuários.

```text
Contato
 ├── Nome
 ├── E-mail
 ├── Mensagem
 └── Botão Enviar
```

---

### Footer

Rodapé institucional.

```text
Footer
 ├── Direitos Autorais
 └── Informações do Projeto
```

---

## Fluxo de Navegação

```text
Início
  │
  ▼
Sobre
  │
  ▼
Ações Sustentáveis
  │
  ▼
Impactos
  │
  ▼
Galeria
  │
  ▼
Contato
  │
  ▼
Rodapé
```

---

## Arquitetura Visual

```text
┌─────────────────────────┐
│        HEADER           │
├─────────────────────────┤
│         HERO            │
├─────────────────────────┤
│         SOBRE           │
├─────────────────────────┤
│         AÇÕES           │
├─────────────────────────┤
│       IMPACTOS          │
├─────────────────────────┤
│       GALERIA           │
├─────────────────────────┤
│       CONTATO           │
├─────────────────────────┤
│        FOOTER           │
└─────────────────────────┘
```

## Padrões Utilizados

- HTML semântico
- CSS responsivo
- Flexbox
- CSS Grid
- Mobile First
- Código organizado por seções
- Fácil manutenção
- Compatível com GitHub Pages
