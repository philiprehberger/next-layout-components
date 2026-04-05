# @philiprehberger/next-layout-components

[![CI](https://github.com/philiprehberger/ts-next-layout-components/actions/workflows/ci.yml/badge.svg)](https://github.com/philiprehberger/ts-next-layout-components/actions/workflows/ci.yml)
[![npm version](https://img.shields.io/npm/v/@philiprehberger/next-layout-components.svg)](https://www.npmjs.com/package/@philiprehberger/next-layout-components)
[![Last updated](https://img.shields.io/github/last-commit/philiprehberger/ts-next-layout-components)](https://github.com/philiprehberger/ts-next-layout-components/commits/main)

Layout primitives for Next.js and React apps

## Installation

```bash
npm install @philiprehberger/next-layout-components clsx
```

## Usage

```tsx
import { Page, Card } from '@philiprehberger/next-layout-components';

export default function HomePage() {
  return (
    <Page maxWidth="xl">
      <Card title="Welcome" padding="lg" hoverable>
        <p>Card content goes here</p>
      </Card>
    </Page>
  );
}
```

## API

### `Page`

Page wrapper with responsive padding and configurable max width.

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `children` | `ReactNode` | -- | Page content |
| `maxWidth` | `'sm' \| 'md' \| 'lg' \| 'xl' \| '2xl' \| 'full'` | `'xl'` | Max width constraint |
| `className` | `string` | -- | Additional CSS classes |

### `Card`

Card container with optional title, configurable padding, and hover effect.

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `children` | `ReactNode` | -- | Card content |
| `title` | `string` | -- | Optional card heading |
| `padding` | `'none' \| 'sm' \| 'md' \| 'lg'` | `'md'` | Padding size |
| `hoverable` | `boolean` | `false` | Enable hover effect |
| `className` | `string` | -- | Additional CSS classes |
| `contentWrapperClassName` | `string` | -- | CSS class for the content wrapper |

## Development

```bash
npm install
npm run build
npm test
```

## Support

If you find this project useful:

⭐ [Star the repo](https://github.com/philiprehberger/ts-next-layout-components)

🐛 [Report issues](https://github.com/philiprehberger/ts-next-layout-components/issues?q=is%3Aissue+is%3Aopen+label%3Abug)

💡 [Suggest features](https://github.com/philiprehberger/ts-next-layout-components/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement)

❤️ [Sponsor development](https://github.com/sponsors/philiprehberger)

🌐 [All Open Source Projects](https://philiprehberger.com/open-source-packages)

💻 [GitHub Profile](https://github.com/philiprehberger)

🔗 [LinkedIn Profile](https://www.linkedin.com/in/philiprehberger)

## License

[MIT](LICENSE)
