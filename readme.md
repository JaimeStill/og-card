# Open Graph Card Format

Used for generating link previews via [Vercel OG Image Playground](https://og-playground.vercel.app) for deployed Docusaurus sites.

**Current Card**: [03-starfield](./designs/03-starfield/)

Profile picture by [bitmoji](https://www.bitmoji.com/).

![og-card](./designs/03-starfield/images/og-card.png)

```jsx
<div
  style={{
    height: '100%',
    width: '100%',
    display: 'flex',
    backgroundColor: '#ffffff',
    fontSize: 38,
    fontWeight: 600
  }}
>
  <div
    style={{
      height: '100%',
      width: 24,
      backgroundColor: '#cb213b'
    }}
  >
  </div>
  <div
    style={{
      height: '100%',
      width: 24,
      backgroundColor: '#e16235'
    }}
  >
  </div>
  <div
    style={{
      height: '100%',
      width: 24,
      backgroundColor: '#deaa47'
    }}
  >
  </div>  
  <div
    style={{
      height: '100%',
      width: 24,
      backgroundColor: '#305282'
    }}
  >
  </div>
  <div
    style={{
      display: 'flex',
      flex: '1 1 auto',
      flexDirection: 'column',
      alignItems: 'center',
      justifyContent: 'center'
    }}
  >
    <img
      src="https://avatars.githubusercontent.com/u/14102723?v=4"
      height="260"
      style={{
        borderRadius: '50%',
        border: '6px solid #333333'
      }}
    />
    <div
      style={{
        marginTop: 40,
        color: '#333333',
      }}
    >
      https://jaimestill.github.io/og-card
    </div>
  </div>
</div>
```