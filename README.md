# AhKite

> UI components, colors, fonts and style for Albatrosses

- Components
- Color
- Fonts
- Reset CSS

## Install

```
npm install @albatrosses/ah-kite
```

## Usage
Import `@albatrosses/ah-kite` and `@albatrosses/ah-kite/styles/index.css` in your root component

```js
import { Language } from "@albatrosses/ah-kite";

const App: React.FC = () => {
  return (
    <Language languages={languages}>
      <AhKite>
        <App />
      </AhKite>
    </Language>
  );
};
```

Then you can use theme in your scss

```tsx
export const ChatWrapper = styled.div`
  background-color: ${paletteHelper(PaletteToken.ColorActive)};
  ${typographyHelp(TypographyToken.Content)};
  ${contourHelp(ContourToken.Primary)};
  ${radiusHelp(RadiusToken.Large)};
`;
```
