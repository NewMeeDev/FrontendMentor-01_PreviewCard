# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 



### Screenshot

![](./screen.png)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Background-Image-Overlay
- Pseudo-Elements

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:
```html
<div class="logo">
  <div class="overlay-effect">
    <img src="images/icon-view.svg" alt="">
  </div>
</div>
```

```css
.logo {
    margin: 20px;
    background: url(images/image-equilibrium.jpg) 0 0 no-repeat; 
    height: 250px;
    background-size: cover;
    border-radius: .5em;;
}

.overlay-effect {
    min-height: 250px;
    opacity: 0;
    transition: 1s ease;
    background-color: rgba(0, 255, 247, 0.7);
    border-radius: .5em;
    display: flex;
    justify-content: center;
    align-items: center;
}

.logo:hover .overlay-effect {
    opacity: 1;
    cursor: pointer;
}
```
