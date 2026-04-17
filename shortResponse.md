# Short Response — LG 7.0: Responsive Units

Answer each question in 2–3 sentences. 

---

## Question 1 — Describe

What is the difference between a static unit like `px` and a responsive unit like `%` or `vh`? 

Describe what makes a unit responsive and why that matters when building a website.

The difference between a static unit like "px" and a responsive unit like "%" or "vh" is that a static unit like "px" does not change size. It is great for small details that should never change size like icons, but its layouts can break on phones or tablets. However, a responsive unit like "%" or "vh" changes based on screen. "%" is relative to the parent container's size, while "vh" is relative to the total height of the browser.

The ability of how it changes based on screen size makes a unit responsive. This matters when building a website because you want your sections and elements to be accessible for everyone no matter their device. It also makes user flow and details easier to analyze because it doesn't break and adapts to the screen size. When adjusting the window, the responsive units adjust to the size of the browser. 




---

## Question 2 — Explain

Look at these two CSS rules:

```css
.image {
  width: 400px;
}

.image {
  width: 50%;
}
```

Explain what happens to the image on a small screen with each rule. Why does one behave better than the other?


The image with 400px as its width stays as 400px on a small screen and it doesn't change. Its layout can break on small screens. The image with 50% as its width takes up 50% of its parent container's size and it changes based on the user's screen size. The image with 50% behaves better than the image with 400px because it doesn't break on certain devices and screens, and it can be changed to fit the screen better.


