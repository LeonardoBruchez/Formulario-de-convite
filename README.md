# 🎉 Formulário de Convite - Festivite

Este projeto foi desenvolvido durante a trilha **Full Stack** da **Rocketseat**, focado no aprendizado de **HTML**, **CSS** e **JavaScript**. O objetivo é criar um formulário interativo para geração de convites digitais para eventos.

## 🎨 Design Original

O projeto foi baseado no design criado pela **Rocketseat** no **Figma**:
- **Link do projeto**: [Figma Community - Formulário de Convite](https://www.figma.com/community/file/1389649528880849780)
- **Objetivo**: Aprender a reproduzir designs do Figma no VS Code
- **Metodologia**: Desenvolvimento guiado com foco na prática de HTML e CSS

## 📋 Descrição do Projeto

O **Festivite** é uma aplicação web que permite aos usuários criar convites digitais personalizados para diversos tipos de eventos. O formulário inclui campos para informações do evento, personalização visual e dados de contato.

## 🛠️ Tecnologias Utilizadas

### **Frontend**
- **HTML5** - Estrutura semântica e formulários
- **CSS3** - Estilização e layout responsivo
- **JavaScript** - Interatividade e validações

### **Frameworks e Bibliotecas**
- **Google Fonts** - Tipografia (Open Sans, Baloo 2, Leckerli One)

## 🎨 Recursos de Design e Layout

### **CSS Grid Layout**
- Layout principal usando `display: grid`
- Grid responsivo para diferentes seções
- Organização em colunas e linhas flexíveis

### **CSS Flexbox**
- Alinhamento de elementos
- Distribuição de espaço
- Layout de componentes internos

### **CSS Custom Properties (Variáveis CSS)**
- Sistema de cores centralizado
- Tipografia padronizada
- Facilita manutenção e consistência

### **Pseudo-classes e Pseudo-elementos**
- Estados de hover e focus
- Validação visual de formulários
- Interações dinâmicas

## 📝 Funcionalidades Implementadas

### **Formulário Completo**
- **Campos de texto** com validação
- **Inputs de data e hora** para início e fim do evento
- **Radio buttons** para tipo de evento (Presencial/Online)
- **Seleção de cores** para personalização
- **Temas de eventos** com ícones
- **Upload de arquivos** para foto de capa
- **Checkboxes** para termos e condições

### **Validação de Formulário**
- Validação HTML5 nativa
- Mensagens de erro personalizadas
- Estados visuais para campos obrigatórios
- Validação em tempo real

### **Design System**
- **Paleta de cores** consistente
- **Tipografia** hierárquica
- **Componentes** reutilizáveis
- **Ícones** SVG otimizados

## 🎯 Conceitos Aprendidos

### **HTML**
- Estrutura semântica com `fieldset` e `legend`
- Formulários complexos com diferentes tipos de input
- Acessibilidade e validação nativa
- Organização de conteúdo

### **CSS**
- **CSS Grid** para layouts complexos
- **Flexbox** para alinhamentos
- **CSS Custom Properties** para design system
- **Pseudo-classes** para interações
- **Media queries** para responsividade
- **Animações** e transições
- **Organização modular** de estilos

### **JavaScript**
- Manipulação do DOM
- Validação de formulários
- Interações dinâmicas
- Event handling

### **Figma para Código**
- **Interpretação de designs** do Figma
- **Conversão de layouts** para HTML/CSS
- **Extração de assets** (ícones, imagens)
- **Aplicação de estilos** baseados no design system
- **Desenvolvimento pixel-perfect** seguindo o mockup

## 📁 Estrutura do Projeto

```
Formulario-de-convite/
├── assets/
│   ├── Background.png
│   ├── event/          # Ícones de eventos
│   └── icons/          # Ícones gerais
├── styles/
│   ├── fieldset/       # Estilos específicos de campos
│   ├── global.css      # Reset e variáveis globais
│   ├── layout.css      # Layout principal
│   ├── form.css        # Estilos de formulário
│   └── index.css       # Arquivo principal de estilos
└── index.html          # Página principal
```

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone [URL_DO_REPOSITORIO]
```

2. Abra o arquivo `index.html` em seu navegador

3. Ou use um servidor local:
```bash
# Com Python
python -m http.server 8000

# Com Node.js
npx serve .
```

## 🎨 Comparação com o Design Original

Para verificar a fidelidade ao design original:
1. Acesse o [projeto no Figma](https://www.figma.com/community/file/1389649528880849780)
2. Compare com a implementação atual
3. Observe a reprodução dos elementos visuais e interações

## 🌐 Deploy

O projeto está configurado para funcionar no **GitHub Pages**. Para fazer o deploy:

1. Faça push para o repositório
2. Vá em Settings > Pages
3. Selecione a branch main
4. O site ficará disponível em: `https://[seu-usuario].github.io/[nome-do-repo]`

## 🔧 Correções Realizadas

### **Problema Identificado e Corrigido:**
- **CSS não carregando no GitHub Pages**: O caminho do CSS estava como absoluto (`/styles/index.css`), foi alterado para relativo (`./styles/index.css`)

## 📱 Responsividade

O projeto foi desenvolvido com foco em:
- Layout responsivo
- Adaptação para diferentes tamanhos de tela
- Experiência do usuário otimizada

## 🎨 Personalização

O formulário permite:
- **12 cores diferentes** para personalização
- **11 temas de eventos** (Aniversário, Casamento, Carnaval, etc.)
- **Modo escuro/claro**
- **Upload de foto de capa**

## 👨‍💻 Desenvolvedor

**Leonardo Bruchez**
- GitHub: [@LeonardoBruchez](https://github.com/LeonardoBruchez)

---

## 📚 Recursos de Aprendizado

- **Rocketseat**: Trilha Full Stack
- **Figma**: Design original e assets
- **VS Code**: Ambiente de desenvolvimento
- **GitHub Pages**: Deploy e hospedagem

*Projeto desenvolvido durante a trilha Full Stack da Rocketseat - 2024* 