# StateKit

A lightweight CSS library for empty, loading, error, and success states.

Most UI libraries focus on structure — buttons, forms, layouts.  
StateKit focuses on the parts that are often implemented late:

- Empty data screens  
- Loading states  
- Error handling  
- First-time user flows  

It provides a small set of consistent, reusable patterns for these cases.

---

## Components

- Empty state  
- Empty search state  
- Error state  
- 404 page  
- Success state  
- Loading spinner  
- Loading skeleton  
- Onboarding state  

---

## Installation

### Option 1: Use directly

Clone the repository:

```bash
git clone https://github.com/roynick365/statekit
```

Then include:

```html
<link rel="stylesheet" href="./src/statekit.css">
```

---

### Option 2: CDN

```html
<link rel="stylesheet" href="https://unpkg.com/statekit-ui/src/statekit.css">
```

---

### Option 3: npm

```bash
npm install statekit-ui
```

```js
import 'statekit-ui/src/statekit.css';
```

---

## Usage

Each component is self-contained and can be used as-is.

```html
<div class="sk-empty">
  <h3>No data available</h3>
  <p>Create your first item to get started.</p>
  <button class="sk-btn">Create</button>
</div>
```

---

## Demo

https://roynick365.github.io/statekit/

---

## Customisation

Override CSS variables to match your setup:

```css
:root {
  --sk-accent: #2D5BE3;
  --sk-text: #1A1917;
  --sk-border: #E4E1D8;
}
```

---

## Status

Initial release. Actively being improved.

---

## Roadmap

- Additional state variants  
- Dark mode support  
- Accessibility improvements  
- Framework wrappers (React)  

---

## Contributing

Contributions and feedback are welcome.  
Open an issue or submit a pull request.

---

## License

MIT
