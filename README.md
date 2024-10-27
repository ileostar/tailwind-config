# @ileostar/tailwind-config

The Tailwind CSS configuration for LeoStar's projects.

## Usage

```bash
pnpm add @ileostar/tailwind-config
```

```ts
// tailwind.config.ts
import sharedConfig from '@ileostar/tailwind-config'
import type { Config } from 'tailwindcss'

const config: Config = {
  darkMode: 'class',
  content: ['./src/**/*.{ts,tsx}'],
  presets: [sharedConfig],
  // ...
}
export default config
```

## License

[MIT](./LICENSE) License © 2024 [ileostar](https://github.com/ileostar)
