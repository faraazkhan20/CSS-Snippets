## mobile view
normally applied,
```css
.text-section {
  font-size: 1.2rem;
  line-height: 1.1;
  padding: 0 5em;
}
```
targets screens with a maximum width of 767px (typically mobile devices), <br>
it'll override the .text-section class,
```css
@media (max-width: 767px) {
  .text-section {
    font-size: 1.2rem;
    line-height: 1.1;
    padding: 0 1em;
  }
}
```
