# 🎉 Birthday Wish Website - Customization Guide

## Welcome Beginner! 👋

This is a beautiful animated birthday website. Here's how to customize it for your needs:

---

## **EASY CUSTOMIZATIONS** (No coding needed, just text editing)

### 1. **Change the Birthday Person's Name**

**Find this line in `index.html`:**
```
<span>Dear Aqsa</span>
```
**Change it to:**
```
<span>Dear [Their Name]</span>
```

**Also find:**
```
<h4 class="username">To: Aqsa 💖<span class="underline"></span></h4>
```
**Change to:**
```
<h4 class="username">To: [Their Name] 💖<span class="underline"></span></h4>
```

---

### 2. **Change the Birthday Date**

**Find this line in `index.html`:**
```javascript
let datetxt = "Your Birthday Date";
```

**Change to:**
```javascript
let datetxt = "25 December";  // or whatever the date is
```

---

### 3. **Change the Birthday Message**

**Find this line in `index.html`:**
```javascript
let datatxtletter = "Write your birthday message here...";
```

**Change to your custom message:**
```javascript
let datatxtletter = "Happy Birthday! You are amazing and I wish you all the best!";
```

---

### 4. **Change Colors**

**Open `style.css` and find these lines at the top:**
```css
:root{
    --color-pink: #feecea;        /* Background color */
    --color-text-pink: #FF7882;   /* Text/Button pink color */
}
```

**Try these color codes:**
- Light Blue: `#e3f2fd`
- Light Green: `#e8f5e9`
- Light Purple: `#f3e5f5`
- Light Yellow: `#fffde7`

---

### 5. **Change the Button Text**

**Find this line in `index.html`:**
```html
<div class="mail">
    Click Here to Open Letter
    <i class="fa-regular fa-envelope"></i>
</div>
```

**Change to:**
```html
<div class="mail">
    Click Here
    <i class="fa-regular fa-envelope"></i>
</div>
```

---

## **HOW TO UPLOAD & VIEW**

### On GitHub:
1. Go to your repository settings
2. Scroll down to "GitHub Pages"
3. Select "main" branch
4. Click Save
5. Wait 1-2 minutes
6. Visit: `https://ranaarbaz5050-ship-it.github.io/Aqsa/`

---

## **NEED IMAGES?**

The website needs these images in an `images/` folder:
- `1.png` (flag image)
- `hat.png` (party hat)
- `unnamed.png` (profile picture)
- `balloon1.png` (balloon 1)
- `balloon2.png` (balloon 2)
- `decorate_flower.png` (flower)
- `decorate.png` (decoration)
- `smiley_icon.png` (smiley)

Download these from the original repo or create simple PNG images.

---

## **EMOJIS YOU CAN ADD**

Add these anywhere in the text:
- 🎉 🎊 🎈 🎂 🥳 💖 ⭐ 🌟 ✨ 🎀 🎁 💝

Example:
```javascript
let datatxtletter = "Happy Birthday! 🎉🎂 Have an amazing day! 💖✨";
```

---

## **TROUBLESHOOTING**

**Q: The page is blank?**
A: Make sure all image files are in the `images/` folder

**Q: The text isn't changing?**
A: Make sure you saved the file and refreshed your browser (Ctrl+F5)

**Q: How do I edit the files?**
A: Click on the file in GitHub → Click the pencil icon → Edit → Commit

---

## **NEXT STEPS**

Once you understand this, try:
- Changing fonts (look for `font-family` in CSS)
- Adjusting animations timing
- Adding more messages

**Happy Coding! 🚀**
