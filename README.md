# 📸 Image Panel Website – Day 1 Project

Welcome to my very first project in my daily coding journey!  
This simple webpage displays a set of image panels that expand when clicked — a great visual and interactive start to building better coding habits.

---

##  What It Does:

- Displays 5 images side-by-side.
- Clicking an image panel **expands** it while collapsing the others.
- Built using **HTML**, **CSS (Flexbox)**, and **JavaScript**.

## 🔍 Preview

![Screenshot of the working project]([/images/screenshot.png])

---

##  What I Learned:

- How to use `querySelectorAll` and loop over elements with `.forEach`.
- How to dynamically add and remove classes in JavaScript.
- Better understanding of **Flexbox** and layout behavior.
- Learned how HTML structure affects styling — especially when using multiple `.container` divs.

---

##  What Went Wrong:

I originally wrapped each image panel inside its own `.container`, which caused weird spacing and layout issues.

### The Fix:
- Placed all `.panel` elements inside **a single `.container`** so Flexbox could arrange them properly in one row.
- Removed redundant `margin` and used `gap` for cleaner spacing.

---

## 🚀 Future Ideas

- Make the layout more responsive for mobile devices.
- Add fade-in transitions or hover effects.
- Load images and captions dynamically.

---

