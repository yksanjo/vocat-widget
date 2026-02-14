# VoCAT-Widget

Embeddable voice terminal widget for any website.

## Features

- Embeddable on any website
- Floating widget or inline mode
- Voice input + text commands
- Customizable themes
- Minimal footprint

## Quick Start

```html
<script src="https://unpkg.com/vocat-widget/dist/vocat.min.js"></script>
<script>
  VoCAT.init({
    apiEndpoint: 'https://your-api.com',
    theme: 'dark',
    position: 'bottom-right'
  });
</script>
```

## Options

| Option | Type | Default | Description |
|--------|------|---------|-------------|
| apiEndpoint | string | '' | API server URL |
| theme | string | 'dark' | 'dark' or 'light' |
| position | string | 'bottom-right' | Widget position |
| voiceEnabled | boolean | true | Enable voice input |
| voices | array | [] | Custom TTS voices |

## Themes

- `dark` - Dark terminal aesthetic
- `light` - Light mode
- `jarvis` - Iron Man inspired
- `peon` - Playful robot style

## Example

```html
<!DOCTYPE html>
<html>
<head>
  <script src="https://unpkg.com/vocat-widget"></script>
</head>
<body>
  <vocat-widget 
    api-endpoint="http://localhost:3000"
    theme="jarvis"
  ></vocat-widget>
</body>
</html>
```

## License

MIT
