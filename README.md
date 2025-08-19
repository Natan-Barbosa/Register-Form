# Formulário de Registro Responsivo

Um formulário de cadastro moderno e responsivo desenvolvido com HTML5 e Tailwind CSS, otimizado para dispositivos móveis e desktop.

## 📋 Descrição

Este projeto apresenta um formulário de registro elegante com design responsivo, featuring uma interface limpa e moderna com efeitos visuais em gradiente roxo. O formulário coleta informações básicas do usuário incluindo dados pessoais, credenciais de acesso e preferências de gênero.

## ✨ Características

- **Design Responsivo**: Adaptação automática para dispositivos móveis e desktop
- **Interface Moderna**: Visual clean com sombras personalizadas e gradientes roxos
- **Layout Flexível**: Grid system responsivo que reorganiza elementos em telas menores

## 🎨 Design Features

- **Tema de Cores**: Paleta roxa com efeitos de sombra personalizados
- **Layout Split**: Imagem lateral no desktop, formulário completo no mobile
- **Efeitos Visuais**: Sombras com gradiente roxo (`#B506DE95`)
- **Tipografia**: Font sans-serif moderna e legível

## 📱 Responsividade

### Desktop (lg+)

- Layout dividido em duas colunas (50/50)
- Imagem de background visível na lateral esquerda
- Formulário organizado em duas colunas para otimização do espaço

### Mobile

- Layout de coluna única
- Imagem de background oculta para maximizar espaço do formulário
- Campos empilhados verticalmente para melhor usabilidade touch

## 🔧 Campos do Formulário

### Informações Pessoais

- **Primeiro Nome**: Campo de texto obrigatório
- **Sobrenome**: Campo de texto obrigatório
- **Email**: Validação de formato de email
- **Celular**: Campo para número de telefone

### Credenciais de Acesso

- **Senha**: Campo de senha com mascaramento
- **Confirmação de Senha**: Verificação de senha

### Dados Adicionais

- **Gênero**: Seleção por radio buttons (Masculino, Feminino, Outros)

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e moderna
- **Tailwind CSS**: Framework CSS utility-first via CDN
- **Responsive Design**: Breakpoints mobile-first

## 📦 Estrutura de Arquivos

```
projeto/
├── index.html          # Arquivo principal do formulário
|── tailwind.config.js  # Arquivo tailwind para que o intelisense funcione
├── assets/
│   └── img/
│       └── img_1.svg   # Imagem de background (lateral)
└── README.md           # Documentação do projeto
```

## 🚀 Como Usar

1. **Clone ou baixe o projeto**

   ```bash
   git clone git@github.com:Natan-Barbosa/Register-Form.git
   ```

2. **Navegue até o diretório**

   ```bash
   cd Register-Form
   ```

3. **Abra o arquivo HTML**
   - Abra `index.html` em qualquer navegador moderno
   - Ou use um servidor local para desenvolvimento

## 🔧 Configuração e Personalização

### Cores do Tema

Para alterar a paleta de cores, modifique as classes do Tailwind:

- `bg-purple-500`: Cor principal dos botões
- `text-purple-500`: Cor do texto principal
- `shadow-[0px_-1px_35px_5px_#B506DE95]`: Sombra personalizada

### Breakpoints Responsivos

- `lg:`: Aplicado em telas ≥ 1024px
- Classes sem prefixo: Aplicadas em todas as telas (mobile-first)

## 🔍 Validações Implementadas

- **Email**: Validação HTML5 nativa de formato
- **Senha**: Campo protegido com mascaramento
- **Gênero**: Seleção obrigatória via radio buttons

## 📄 Licença

Desenvolvido com com o intuito de aprendizado
