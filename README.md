# StateKit

A lightweight CSS library for empty, loading, error, and success states.

Most UI libraries focus on structure — buttons, forms, layouts.  
StateKit focuses on the parts that are often left until the end:

- Empty data screens
- Loading states
- Error handling
- First-time user flows

The goal is to provide consistent, reusable patterns for these cases.

---

## Components

- Empty State
- Empty Search
- Error State
- 404 Page
- Success State
- Loading Spinner
- Loading Skeleton
- Onboarding State

---

## Installation

### CDN
```html
<link rel="stylesheet" href="https://unpkg.com/statekit-ui/src/statekit.css">
```

### npm
```bash
npm install statekit-ui
```
```js
import 'statekit-ui/src/statekit.css';
```

### Copy-paste

Use `src/statekit.css` directly.

---

## Usage

```html
<div class="sk-empty">
  <h3>No data available</h3>
  <p>Create your first item to get started.</p>
  <button class="sk-btn">Create</button>
</div>
```

---

## Customisation

```css
:root {
  --sk-accent: #2D5BE3;
  --sk-text: #1A1917;
  --sk-border: #E4E1D8;
}
```

---

## Roadmap

- Dark mode
- React wrappers
- Additional state variants
- Accessibility improvements

---

## License

MIT
