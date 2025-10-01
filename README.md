# WDS Shadcn Registry - Accessible Component Library

A comprehensive collection of accessible, customizable UI components built specifically for use with Shadcn/ui and modern React applications.

## Features

- ♿ **Accessibility First** - All components built with accessibility in mind
- 🎨 **Customizable** - Easy theming and styling options
- 📦 **Ready to Use** - Pre-built components for common UI patterns
- 🔧 **TypeScript** - Full TypeScript support with proper type definitions
- 📱 **Responsive** - Mobile-first design approach
- ⚡ **Performance** - Optimized for fast loading and smooth interactions

## Components Included

### Form Components
- Input fields with validation
- Textarea with auto-resize
- Select dropdowns
- Checkbox and radio groups
- Form validation helpers

### Navigation
- Breadcrumb navigation
- Tab components
- Sidebar navigation
- Mobile-friendly menus

### Data Display
- Tables with sorting and filtering
- Cards and layouts
- Progress indicators
- Status badges

### Interactive Elements
- Modal dialogs
- Dropdown menus
- Tooltips and popovers
- Loading states and skeletons

## Tech Stack

- **React** - Component framework
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Shadcn/ui** - Component foundation
- **Radix UI** - Accessibility primitives

## Installation

```bash
npm install wds-shadcn-registry
# or
yarn add wds-shadcn-registry
# or
pnpm add wds-shadcn-registry
```

## Usage

```tsx
import { Button, Card, Input } from 'wds-shadcn-registry'

export default function MyComponent() {
  return (
    <Card>
      <Input placeholder="Enter your name" />
      <Button>Submit</Button>
    </Card>
  )
}
```

## Development

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn or pnpm

### Setup

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests to improve the component library.

## License

MIT License
