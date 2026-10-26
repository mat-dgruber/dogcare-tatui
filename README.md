# dogcare-tatui

Dog Care Tatuí — Creche & Hotel Canino livre de gaiolas.

## Estrutura

- `creche/` — Landing Page institucional (Next.js 15 + Tailwind, export estático)
- `paraiso/` — Sistema de gestão (pnpm workspace: admin, pátio, recepção, hotel, financeiro, estética, prontuário, gestão e configurações + pacote `@monvet/domain`)

## Desenvolvimento

```bash
# Landing Page
cd creche && pnpm install && pnpm dev

# Sistema de gestão
cd paraiso && pnpm install && pnpm build && pnpm dev
```
