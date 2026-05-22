# @omnibioai/design-tokens

OmniBioAI unified design system tokens — 47 CSS custom properties covering colors, typography, spacing, and layout.

## Usage

### CSS
```css
@import '@omnibioai/design-tokens/tokens.css';
```

### JS/ESM
```js
import { tokens } from '@omnibioai/design-tokens';
```

## Token categories

| Category | Tokens |
|---|---|
| Backgrounds | `--color-bg`, `--color-bg-surface`, `--color-bg-surface2`, `--color-bg-surface3`, `--color-bg-elevated` |
| Borders | `--color-border`, `--color-border-muted`, `--color-border-bright` |
| Text | `--color-text`, `--color-text-soft`, `--color-text-secondary`, `--color-text-muted`, `--color-text-dim` |
| Brand | `--color-accent`, `--color-blue`, `--color-purple` (+ `-dim`/`-surface`/`-border` variants) |
| Status | `--color-danger`, `--color-warning`, `--color-success`, `--color-info` (+ `-dim`/`-border` variants) |
| Shadows | `--shadow-sm`, `--shadow-card`, `--shadow-header` |
| Typography | `--font-sans`, `--font-mono`, `--font-size-xs` → `--font-size-2xl` |
| Border radius | `--radius-xs`, `--radius-sm`, `--radius`, `--radius-lg`, `--radius-xl`, `--radius-pill` |
| Layout | `--sidebar-w`, `--topbar-h`, `--scrollbar-w` |

## Consuming apps

Phase 1 adopters: `omnibioai-lims`, `omnibioai-rag`, `omnibioai-dev-hub`, `omnibioai-control-center`

Phase 2 (planned): `omnibioai-model-registry`, `omnibioai-tes`, `omnibioai-tool-images`
