# @philiprehberger/next-layout-components

[![CI](https://github.com/philiprehberger/next-layout-components/actions/workflows/publish.yml/badge.svg)](https://github.com/philiprehberger/next-layout-components/actions/workflows/publish.yml)
[![npm version](https://img.shields.io/npm/v/@philiprehberger/next-layout-components.svg)](https://www.npmjs.com/package/@philiprehberger/next-layout-components)
[![License](https://img.shields.io/github/license/philiprehberger/next-layout-components)](LICENSE)

Layout primitives for Next.js and React apps.

## Installation

```bash
npm install @philiprehberger/next-layout-components clsx
```

## Components

### `Page`

Page wrapper with responsive padding and configurable max width.

```tsx
import { Page } from '@philiprehberger/next-layout-components';

<Page maxWidth="xl">
  <h1>My Page</h1>
  <p>Content goes here</p>
</Page>
```

Max widths: `sm`, `md`, `lg`, `xl`, `2xl`, `full`

### `Card`

Card container with optional title and hover effect.

```tsx
import { Card } from '@philiprehberger/next-layout-components';

<Card title="Section Title" padding="lg" hoverable>
  <p>Card content</p>
</Card>
```


## Development

```bash
npm install
npm run build
npm test
```

## License

MIT
