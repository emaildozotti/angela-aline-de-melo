# Angela Melo — Landing Page

## Sobre
Landing Page da Angela Melo (Psicanálise, Inteligência Emocional, Mentoria para Mulheres Cristãs).
Gerada pelo pipeline v9 da Zotti Performance Marketing.

## Stack
- React 19 + Vite 6 + Tailwind v4 + Framer Motion v12
- Fontes: Lora (display) + DM Sans (sans)
- Deploy: Vercel (auto via GitHub push)

## Comandos
- `npm run dev` — servidor local
- `npm run build` — build de produção
- `npm run preview` — preview do build

## Edição
- **Copy:** editar `const COPY` em cada componente (`src/components/*.tsx`)
- **Dados:** editar `src/site.config.ts`
- **Cores/Fontes:** editar `@theme` em `src/index.css`
- **Fotos:** substituir `public/foto-hero.jpg` e `public/foto-about.jpg`

## Deploy
```bash
git add -A && git commit -m "update: ..." && git push origin main
```
O Vercel redeploya automaticamente em ~30s.
