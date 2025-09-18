---
name: Matthew
about: Structured checklist for reviewing a classmate's Queen’s Student Page
title: "Peer Review: Matthew reviewing SamuelSavarie"
labels: peer-review
assignees: Sam S
---

**Live URL:** https://github.com/SamuelSavarie/Queens-Student-Page/actions/runs/17815478769  
**Repo:** https://github.com/SamuelSavarie/Queens-Student-Page

### 1) Functionality
- [x] Page loads; links & images work.  
Everything works correctly.

### 2) Clarity / Content
- [x] Clear headings; intro explains who/what.  
Headings are structured, and the intro is clear.

### 3) Accessibility
- [x] All images have alt text; heading levels are logical.  
The `alt` tag says "Your Name portrait" instead of the actual name. Update it to "Portrait of Samuel Savarie" for clarity.

### 4) Style / CSS
- [x] Consistent colors; styles in style.css.  
CSS is linked correctly.

### 5) Performance
- [x] Images are not huge; widths/heights set.  
The image is sized at 240x240, which is good.

### 6) Documentation
- [ ] README tells how to update; commit messages are descriptive.  
Make sure your README includes update instructions. Commit messages could be more descriptive.

### 7) Concrete Suggestion (include code if helpful)
Change the image alt text:
```html
<img src="me.png" alt="Portrait of Samuel Savarie" width="240" height="240" />