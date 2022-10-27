# svg-icon.js

An SVG icon component for the web. Optimized for smooth design and development experience. Fits into any web framework and can be used anyhow.

```html
<svg-icon size="”80px”" color="”gray”">arrow</svg-icon>
```

## Setting things up

1. Install with NPX:

   ```
   npx @rainbowapp/svg-icon.js
   ```

   Or, you can get it going quickly with Unpkg CDN:

   ```
   <script src="https://unpkg.com/@rainbowapp/svg-icon.js/dist/svg-icon.min.js"></script>
   ```

2. Place all of your icons in the new `/icons` folder created at your root directory (or create it yourself).
3. Use `icons/svg-icon.config.json` (or create it yourself) to set the default `source`, `color` and `size`.

   ```html
   { "src": "icons", "name": "logos/logo", "size": 24 }
   ```

4. Use `icons/icons.html` to view all your icons in a simple, organized, and searchable manner.

You’re ready to go!

## Usage

1. Set the `icon-name` within the element’s content.

   ```html
   <svg-icon>arrow</svg-icon>
   ```

   Or, you can do `folder/icon-name` if you’ve categorized your library into folders.

   ```html
   <svg-icon>arrows/right</svg-icon>
   ```

   Override the source directly by setting a different one in the `src` attribute. You can Either use internal or external links.

   ```html
   <svg-icon
     src="https://en.wikipedia.org/wiki/Google_logo#/media/File:Google_2015_logo.svg"
   ></svg-icon>
   ```

2. Colors are one of the main reasons `svg-icon.js` was created!
   Fills are set by default to the font's inherited color, therefore can be overridden with plain CSS selectors using the `color` property:

   ```html
   <div style="color: red;">
     <svg-icon size="80">arrow</svg-icon>
   </div>
   ```

3. You can set the `size` directly (or simply apply your own CSS).

   ```html
   <svg-icon size="80">arrow</svg-icon>
   ```

## Dependencies

Many thanks to [svg-inject](https://github.com/iconfu/svg-inject) for enabling the passing of properties to SVG files.

## Documentation

Visit [svg-icon.fyi](https://svg-icon.fyi) to view the full documentation.

## Community

The svg-icon.js community can be found on [GitHub Discussions](https://github.com/rnbwdev/svg-icon.js/discussions), where you can ask questions, voice ideas, and share your projects.

Join [Rainbow&#39;s Discord](https://discord.com/invite/HycXz8TJkd) to chat with other community members about svg-icon.js.

## Contributing

Please see our [contributing.md](https://github.com/rnbwdev/svg-icon.js/blob/main/contributing.md).

That's it! 🎉
