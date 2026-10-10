# Fitness App - Landing Page

Uma página de apresentação moderna e responsiva para um aplicativo de acompanhamento de vida fitness.

## 📱 Sobre o Projeto

Este é um website estático que apresenta os principais recursos de um app de fitness, desenvolvido com **HTML5** e **CSS3**. A página foi construída com a abordagem **mobile-first**, garantindo uma excelente experiência em todos os dispositivos.

## ✨ Características

- **Responsivo**: Otimizado para mobile, tablet e desktop
- **Design Moderno**: Interface clean e intuitiva
- **Performance**: Otimizado para velocidade de carregamento
- **Acessibilidade**: Semântica HTML adequada
- **Mobile-First**: Desenvolvido com foco em dispositivos móveis

## 🎯 Seções Principais

### Header
- Logo "F" (marca do app)
- Botão de download destacado

### Hero Section
- Headline principal com chamada para ação
- Imagem do app em destaque
- Listagem de principais benefícios:
  - ❤️ Saúde
  - 🏃 Exercício
  - 👯 Amigos

### Features
Três seções alternadas apresentando recursos principais:

1. **Contagem de Calorias** - Controle total do consumo diário
2. **Exercícios que Fazem Sentido** - Organização de treinos personalizados
3. **Compartilhe com Amigos** - Motivação através da comunidade

### Call-to-Action (CTA)
- Botão de download destacado
- Informação de que o app é totalmente gratuito

### Footer
- Informação de copyright

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Styling e responsividade
- **Google Fonts** - Fonte Roboto

## 📁 Estrutura de Arquivos

```
projeto html-css/
├── index.html      # Arquivo HTML principal
├── style.css       # Estilos CSS
├── images/         # Pasta com imagens do app
│   ├── print_1.png
│   ├── print_2.png
│   ├── print_3.png
│   └── print_4.png
└── README.md       # Este arquivo
```

## 🎨 Paleta de Cores

- **Verde Primário**: `#0ebe0b` - Botões e elementos de ação
- **Fundo**: `#ffffff` - Branco puro
- **Texto Primário**: `#333333` - Cinza escuro
- **Fundo Alternado**: `#f8f8f8` - Cinza claro (cards)

## 📱 Breakpoints Responsivos

- **Mobile**: até 767px (padrão)
- **Tablet**: 768px a 1023px
- **Desktop**: 1024px em diante

## 🚀 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/RodrigoR92/meu-projeto.git
```

2. Navegue até o diretório:
```bash
cd projeto\ html-css
```

3. Abra o arquivo `index.html` em seu navegador favorito

Não há dependências externas além da fonte do Google Fonts, que é carregada via CDN.

## 💡 Destaques do Código

### Mobile-First Approach
Os estilos base são aplicados para dispositivos móveis, com media queries que adicionam estilos para telas maiores:
- `@media (min-width: 768px)` - Tablets
- `@media (min-width: 1024px)` - Desktops

### Layout Flexbox
Uso extensivo de Flexbox para alinhamento e distribuição de elementos, garantindo flexibilidade e responsividade.

### Unidades Responsivas
- `clamp()` para tamanhos de fonte fluidos
- `min()` para limitação de largura de imagens
- `max-width` para contenção de conteúdo

## 📸 Imagens Necessárias

As imagens devem ser organizadas na pasta `images/`:
- `print_1.png` - Screenshot principal do app
- `print_2.png` - Tela de contagem de calorias
- `print_3.png` - Tela de exercícios
- `print_4.png` - Tela de compartilhamento

## 🔧 Customização

### Alterar Cores
Modifique os valores das cores no `style.css`:
- Cor verde: procure por `#0ebe0b`
- Cor de fundo: procure por `#ffffff`
- Cores de texto: procure pelos valores em escala de cinza

### Alterar Textos
Edite o `index.html` para alterar:
- Título do app
- Descrições de features
- Qualquer outro conteúdo textual

## 📝 Licença

Todos os direitos reservados - Conforme indicado no rodapé do website.

## 👤 Autor

Desenvolvido por Rodrigo R92

---

**Nota**: Este é um projeto de landing page estática. Para funcionalidades de download, será necessário integrar com um backend ou direcionar para lojas de aplicativos (App Store, Google Play).
