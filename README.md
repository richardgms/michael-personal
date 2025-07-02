# 🔥 Michael Fire Martins - Personal Trainer Website

Site do Personal Trainer Michael Martins com paleta **Fire/Energy** - transformação EXTREMA através de metodologia científica. Queime gordura, ganhe músculo, MUDE SUA VIDA!

## 🚀 Tecnologias

- **Next.js 14** com App Router
- **React 18** 
- **TypeScript**
- **Tailwind CSS** com tema Fire customizado
- **Framer Motion** para animações
- **Lucide React** para ícones

## 🎨 Design System Fire

### Paleta de Cores
- **Primary (Fire)**: `#DC2626` - Vermelho intenso 
- **Secondary (Energy)**: `#EA580C` - Laranja vibrante
- **Accent (Power)**: `#F59E0B` - Amarelo dourado

### Efeitos Especiais
- **Fire Gradient**: Gradiente vermelho → laranja → amarelo
- **Glow Effects**: Brilho neon com cores fire
- **Fire Animations**: Flicker, pulse, particles
- **Neon Text**: Efeito de texto neon com cores fire

## 📁 Estrutura do Projeto

```
michael-fire-personal-trainer/
├── app/
│   ├── globals.css          # Estilos globais + classes Fire
│   ├── layout.tsx           # Layout principal com SEO
│   └── page.tsx             # Página principal
├── components/
│   ├── Navigation.tsx       # Navegação Fire com logo animado
│   ├── HeroSection.tsx      # Hero com partículas fire
│   ├── PlansSection.tsx     # Planos Fire/Beast com preços
│   ├── ResultsSection.tsx   # Transformações explosivas
│   ├── AboutSection.tsx     # Sobre Michael Fire
│   ├── CTASection.tsx       # CTA final "Pegar Fogo"
│   ├── Footer.tsx           # Footer Fire
│   └── WhatsAppButton.tsx   # Botão WhatsApp fixo animado
├── designs/
│   └── design.json          # Sistema de design completo
├── package.json
├── tailwind.config.js       # Configuração Fire + animações
├── tsconfig.json
├── next.config.js
└── postcss.config.js
```

## 🔧 Instalação e Configuração

### 1. Instalar Dependências

```bash
# Instalar Node.js v18 ou superior
# Instalar dependências
npm install
```

### 2. Configurar Ambiente de Desenvolvimento

```bash
# Iniciar servidor de desenvolvimento
npm run dev
```

O site estará disponível em `http://localhost:3000`

### 3. Scripts Disponíveis

```bash
npm run dev          # Desenvolvimento
npm run build        # Build de produção
npm run start        # Iniciar produção
npm run lint         # Verificar código
npm run type-check   # Verificar TypeScript
```

## 🔥 Funcionalidades Fire

### Navegação Intensa
- Logo Fire animado com efeito flicker
- Menu desktop/mobile responsivo
- Botão CTA "QUEIMAR AGORA" com glow
- Backdrop blur com bordas fire

### Hero Section Explosiva
- Partículas fire animadas
- Título gigante com gradiente
- Métricas impressionantes (500+ transformados)
- CTAs para WhatsApp e resultados
- Cards flutuantes com badges

### Planos EXTREMOS
- **Online Fire**: R$80 mensal, R$210 trimestral, R$660 anual
- **Presencial Beast**: R$300 (3x), R$400 (4x), R$500 (5x)
- Cards com hover effects e glow
- Links diretos para WhatsApp

### Resultados Explosivos
- 3 cases de transformação
- Cards interativos com badges
- Efeitos hover fire
- Avaliações 5 estrelas

### Sobre Michael Fire
- Apresentação como Fire Master
- Especialidades: Biomecânica Fire + Avaliação Beast
- Cards de competências animados
- Foto com elementos flutuantes

### CTA Final Intenso
- Background fire gradient
- Título gigante "PEGAR FOGO?"
- Botão premium com animações
- Ícones de benefícios

### Footer Completo
- Logo fire animado
- 4 colunas organizadas
- Contatos e horários
- Links de serviços

### WhatsApp Fire
- Botão fixo bottom-right
- Animação bounce + rings
- Link direto com mensagem
- Ícone SVG WhatsApp

## 📱 WhatsApp Integration

Todos os botões levam para:
**+55 83 98123-8895**

### Mensagens Personalizadas:
- Navegação: "Olá Michael! Vim pelo site e quero saber sobre os planos."
- Hero: "Olá Michael! Quero QUEIMAR gordura agora!"
- Plano Online: "Olá Michael! Quero o plano ONLINE FIRE!"
- Plano Presencial: "Olá Michael! Quero o plano PRESENCIAL BEAST!"
- Resultados: "Olá Michael! Quero ver mais transformações FIRE!"
- Metodologia: "Olá Michael! Quero conhecer a metodologia FIRE!"
- CTA Final: "Olá Michael! Vim pelo site e quero PEGAR FOGO!"

## 🎯 SEO Otimizado

### Meta Tags
- Título: "Michael Fire Martins - Personal Trainer | Transformação EXTREMA"
- Descrição otimizada para conversão
- Keywords relevantes para personal trainer PB
- Open Graph para redes sociais
- Schema.org structured data

### Performance
- Next.js 14 otimizado
- Imagens otimizadas
- CSS Tailwind minificado
- Fonts preloaded
- Compressão gzip

## 🎨 Customização Fire

### Cores no tailwind.config.js
```javascript
colors: {
  primary: { 500: '#DC2626', 600: '#B91C1C' },
  secondary: { 500: '#EA580C', 600: '#C2410C' },
  accent: { 500: '#F59E0B', 600: '#D97706' }
}
```

### Animações Fire
```css
.fire-flicker      # Tremulação fire
.fire-glow         # Brilho pulsante
.fire-particle     # Partículas flutuantes
.neon-fire         # Texto neon
```

### Classes Utilitárias
```css
.fire-gradient     # Gradiente fire
.glow-effect       # Brilho básico
.glow-intense      # Brilho intenso
.btn-fire          # Botão fire padrão
.card-fire         # Card fire padrão
```

## 🚀 Deploy

### Vercel (Recomendado)
```bash
npm install -g vercel
vercel --prod
```

### Netlify
```bash
npm run build
# Upload pasta .next para Netlify
```

### VPS/Servidor
```bash
npm run build
npm start
```

## 📊 Analytics e Conversão

### Eventos Importantes
- Clique WhatsApp (todos os CTAs)
- Scroll até planos
- Clique nos planos
- Tempo na página
- Clique resultados

### Métricas Fire
- Taxa de conversão WhatsApp
- Plano mais escolhido
- Seção com mais engajamento
- Tempo médio de sessão

## 🔧 Manutenção

### Atualizar Preços
Editar valores em:
- `components/PlansSection.tsx`
- `components/HeroSection.tsx` (se necessário)

### Adicionar Resultados
Editar array em:
- `components/ResultsSection.tsx`

### Modificar Cores
Editar:
- `tailwind.config.js`
- `app/globals.css`

## 📞 Suporte

Para dúvidas sobre o código:
- Abrir issue no repositório
- Verificar documentação Next.js
- Consultar documentação Tailwind

---

**🔥 MICHAEL FIRE MARTINS - TRANSFORMAÇÃO EXTREMA!**

> *"Queime gordura, ganhe músculo, MUDE SUA VIDA!"* 