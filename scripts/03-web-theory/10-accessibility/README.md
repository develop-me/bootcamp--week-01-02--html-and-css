# Accessibility
---

### What

- Transport: Inclusive mobility
- About making it available for EVERYBODY
- Not excluding - not catering for a specific subset

---

### Who

- Sight
- Hearing
- Learning difficulties
- Mobility difficulties
- Colour Blindness
- YOU (imagine if you broke your wrist)

---

### Why

- Users == Money/Revenue
- Readable code == happy developers (more productive == money!)
- Legal requirement (Don’t get sued == money!) [http://www.lflegal.com/2017/06/winn-dixie/](http://www.lflegal.com/2017/06/winn-dixie/)

---

### How

- Write good code - use the right element for the right content
- Check design - colours, fonts, interface
- Test: Wave Accessibility Tool [http://wave.webaim.org/](http://wave.webaim.org/)

---

### Consider

- Video captioning
- Big enough buttons
- Cluttered/busy/animated pages
- Lots of text (20ish words per line)
- Font size

---

- Not just using colour as feedback
- Colour contrast
- Zoomable
- Images of text

---

### Aria attributes

In case you use elements that aren't for what they're suppose to be for

For when you want to give users more information about those elements & modules

[https://www.w3.org/TR/html-aria/](https://www.w3.org/TR/html-aria/)

---

### Screen readers use aria

```html
<button aria-label="Close" onclick="myDialog.close()">X</button>
```

http://www.heydonworks.com/article/aria-label-is-a-xenophobe



