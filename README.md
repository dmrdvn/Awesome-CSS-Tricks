# Awesome-CSS-Tricks
In this repo, I'll list some of the CSS trics I like what make things easy.
I hope these tricks make things easier for you when writing CSS.


- [**Show Button with Focus**](https://github.com/dmrdvn/Awesome-CSS-Tricks)
```CSS
button {
    display: none;
}

input:not(:placeholder-shown) + button {
    display: block;
    }
```
![Show Button with Focus Example](Awesome-CSS-Tricks/ShowButtonWithFocus.gif)

