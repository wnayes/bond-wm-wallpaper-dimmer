# bond-wm-wallpaper-dimmer

A simple wallpaper plugin for the [bond-wm window manager](https://github.com/wnayes/bond-wm).

This plugin is meant to be used on top of others. It puts a semi-transparent layer over the wallpaper display,
which darkens in the evening.

## Development

    npm install
    npm run build

## Usage

Import from `@wnayes/bond-wm-wallpaper-dimmer` and render the dimmer component in your desktop's work area.

```tsx
import Dimmer from "@wnayes/bond-wm-wallpaper-dimmer";

<Desktop>
  <WorkArea>
    <Wallpaper />
    <Dimmer /> {/* Put above your desktop wallpaper! */}
  </WorkArea>
</Desktop>;
```

### Configuration

No configuration options are available at this time.

In the future, the time range / darkness could be made configurable.

## License

[MIT License](LICENSE.md)
