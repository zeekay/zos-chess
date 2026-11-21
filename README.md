# ♟️ Chess

[![Open in Hanzo](https://hanzo.app/badges/open-in-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/zeekay/zos-chess&ref=main&action=open) [![Edit with Hanzo](https://hanzo.app/badges/edit-with-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/zeekay/zos-chess&ref=main&action=edit)

Classic chess with AI opponent

## Category
`games`

## Installation

```bash
npm install @anthropic/chess
# or
pnpm add @anthropic/chess
```

## Usage

```tsx
import App from '@anthropic/chess';

function MyComponent() {
  return <App onClose={() => console.log('closed')} />;
}
```

## Development

```bash
# Install dependencies
pnpm install

# Build
pnpm build

# Watch mode
pnpm dev
```

## zOS Integration

This app is designed to run within zOS, a web-based operating system. It follows the zOS app specification with:

- Standalone React component
- TypeScript support
- Tailwind CSS styling
- Window management integration

## License

MIT
