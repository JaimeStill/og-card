# Wavy Gradient

Background by Sean Sinclair via [unsplash.com](https://unsplash.com/photos/2jYK_Bloby4).  

Profile picture by [bitmoji](https://www.bitmoji.com/).  

![og-card](./images/og-card.png)

```jsx
<div
  style={{
    height: '100%',
    width: '100%',
    display: 'flex',
    backgroundImage: 'url(https://images.unsplash.com/photo-1624115773145-9b77fe912897?ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&fit=crop&w=800&h=400&fm=png&crop=bottom)',
    backgroundColor: '#333',
    backgroundRepeat: 'no-repeat',
    backgroundSize: 'cover',
    fontSize: 38,
    fontWeight: 600
  }}
>
  <div
    style={{
      height: '100%',
      width: '100%',
      display: 'flex',
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
        border: '3px solid #fff'
      }}
    />
    <div
      style={{
        marginTop: 40,
        backgroundImage: 'linear-gradient(90deg, #0064c2, #0dffff, #ffbd27, #ff3000)',
        backgroundClip: 'text',
        '-webkit-background-clip': 'text',
        color: 'transparent',
      }}
    >
      https://jaimestill.github.io/og-card
    </div>
  </div>
</div>
```