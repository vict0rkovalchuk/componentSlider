# componentSlider

How to use?

1.  This goes to the `<body>` of your page:

    ```
    <div class="lightbox js-lightbox" style="z-index: 1000">
      <div class="lightbox__overlay"></div>

      <div class="lightbox__content">
        <img class="lightbox__image" src="" alt="" />
      </div>

      <div class="btn-prev"></div>
      <div class="btn-next"></div>

      <button
        type="button"
        class="lightbox__button"
        data-action="close-lightbox"
      >
        &#x292C;
      </button>
    </div>
    ```

2.  Then, wherever you want the gallery in your page `<body>`:

```
<div class="gallery">
    <img src="#" />
    <img src="#" />
    <img src="#" />
</div>
```

3.  Include style.css and slider.js files. Paste this line to your js file where you want to use this slider:
    `import Gallery from './slider';`

    Finally, for using just call init method with your class name:
    `new Gallery('gallery').init();`

_[Example]: https://vict0rkovalchuk.github.io/gallery/_

4. Enjoy!
