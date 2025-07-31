# 🎬 GitHub Unwrapped - Versão Simplificada

Este é o projeto GitHub Unwrapped simplificado, mantendo apenas a parte de renderização de vídeo com dados mockados.

## 🚀 Começando

### Instalação

```bash
# Instale as dependências
npm install

# Abra o Remotion Studio
npm run studio

# Renderize o vídeo
npm run render Main out/video.mp4
```

## 🎨 Customização

### Editando os dados do vídeo

Abra `remotion/mock-data.ts` e edite os valores:

```typescript
export const MOCK_DATA = {
  login: "Seu Nome",
  totalContributions: 1847,
  starsGiven: 150,
  // ... outros dados
}
```

### Cores dos foguetes disponíveis
- `blue`
- `orange`
- `yellow`

### Planetas disponíveis
- `Ice` - Contribuições baixas
- `Leafy` - Contribuições médias baixas
- `Fire` - Contribuições médias
- `Silver` - Contribuições altas
- `Gold` - Contribuições muito altas

## 📐 Estrutura

```
remotion/
├── mock-data.ts      # Dados mockados para o vídeo
├── Root.tsx          # Composições principais
├── Main.tsx          # Vídeo principal
└── [cenas]/          # Diferentes cenas do vídeo
```

## 🎬 Renderização

```bash
# Renderizar em alta qualidade
npm run render Main out/video.mp4 -- --quality 100

# Renderizar com foguete específico
npm run render Main out/video.mp4 --props='{"rocket":"orange"}'
```

## 📄 Licença

Baseado no projeto original GitHub Unwrapped da Remotion.