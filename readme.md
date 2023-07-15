# Open Graph Card Format

Used for generating link previews via [Vercel OG Image Playground](https://og-playground.vercel.app) for deployed Docusaurus sites.

**Resolution**: `1280x640`

> In the OG Playground, set the contaienr height and width to half of this resolution to generate an image at this resolution.

**Current Card**: [03-starfield](./designs/03-starfield/)

Profile picture by [bitmoji](https://www.bitmoji.com/).

![og-card](./designs/03-starfield/images/og-card.png)

## Template

```jsx
<div
  style={{
    height: '100%',
    width: '100%',
    display: 'flex',
    backgroundColor: '#ffffff',
    fontWeight: 600,
    fontSize: 22
  }}
>
  <div
    style={{
      display: 'flex',
      flex: '1 1 auto',
      margin: 40,
      border: '3px solid #333333',
      borderRadius: 25
    }}
  >
    <div
      style={{
        display: 'flex',
        flex: '1 1 auto',
        flexDirection: 'column',
        alignItems: 'center',
        justifyContent: 'center',
        gap: '24px'
      }}
    >
      <img
        src="https://avatars.githubusercontent.com/u/14102723?v=4"
        height="148"
        style={{
          borderRadius: '50%',
          border: '3px solid #333333'
        }}
      />
      <div
        style={{
          color: '#333333'
        }}
      >
        https://jaimestill.github.io/repository
      </div>
    </div>
  </div>
</div>
```