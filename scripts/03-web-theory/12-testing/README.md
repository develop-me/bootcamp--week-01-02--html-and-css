# CSS Testing & Performance
---

## Testing your code

---

![Lots and lots of devices](day05/02TestingAndPerformance/devices.png)

---

### Cross browser & cross device

- Testing on different browsers & devices
- Browser testing tools
    - [https://www.browserstack.com/](https://www.browserstack.com/)
    - [https://crossbrowsertesting.com/pricing](https://crossbrowsertesting.com/pricing)
    - [https://www.browserling.com/](https://www.browserling.com/)
    - Dev tools

---

## Aside: Browser support

---

### Loads of different browsers out there

- Loads of different CSS & HTML specs (& JavaScript too!)
- Things may not be supported
- Things may render differently
- Things may be old
- Things may be new

---

### Can I use?

[caniuse.com](www.caniuse.com)

---

### What if I want to use something new & support old browsers?

- Polyfills
- `@supports`
- Have your website work without it

---

### Remember Modernizr

[https://modernizr.com/](https://modernizr.com/)

Detect features, add classes, harness this to add support/polyfills

---

### Validate your code

- HTML [https://validator.w3.org/](https://validator.w3.org/)
- CSS [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)

---

### Accessibility

- Wave accessibility check [https://wave.webaim.org/](https://wave.webaim.org/)

---

### Devtools Audit

- Google Lighthouse
    - Devtools (it's open already right 🤓) Go to `Audits` tab

---

## Aside: Performance

---

### Data

Network: Modems, 2G, 3G, 4G, Broadband, Cable

Everything that makes an app or website is made of data, that data needs to be served over the network

Thus it needs to be downloaded

---

### But why tho?

- Users don’t like waiting (2 secs max)
- Users have data plans
- Users may not have good connections

---

### So?

- Users == Money/Revenue
- Amazon reduce their load speed by 1ms - reduce revenue by 1%

---

### How

- Write good *concise* DRY code
- Asset management
    - Compress images
    - Lazy loading
- First paint

There are many many techniques to do with performance - you will learn a lot more of this over your career, but suffice to say start with good clean code

---

## Back to testing

---

### Real life testing

![App design](day05/02TestingAndPerformance/app.png)

---

![App on tablet](day05/02TestingAndPerformance/appTab.png)

---

### All the links

[Are here 🤓](https://github.com/develop-me/fellowship-wk1-beg-html-css/blob/master/day05/01TestingAndPerformance/README.md)







