# **Understanding the `<img>` Tag in HTML**  

The `<img>` tag in HTML is used to add pictures to a webpage. It helps make websites more fun and interesting by displaying images like photos, logos, or icons.  

---

## **1. How Does the `<img>` Tag Work?**  
The `<img>` tag does **not** have a closing tag because it only has one part: the opening tag. To use it, we need to provide a few important **attributes** (extra information) so the browser knows which image to show.

### **Basic Example:**  
```html
<img src="flower.jpg" alt="A beautiful pink flower">
```

---

## **2. Important Attributes of the `<img>` Tag**
### **a) `src` (Source) – Where the Image Comes From**
- The `src` attribute tells the browser **where to find the image**.  
- It can be from your computer or the internet.  

**Example 1: Image from the same folder**
```html
<img src="cat.jpg" alt="A cute cat">
```

**Example 2: Image from the internet**
```html
<img src="https://example.com/cat.jpg" alt="A cute cat">
```

### **b) `alt` (Alternative Text) – For Accessibility**
- The `alt` text **describes the image** in case it doesn’t load or for people who can’t see it.  
- It is important for **blind users** who use screen readers.  

**Example:**  
```html
<img src="sunset.jpg" alt="A beautiful sunset over the ocean">
```

If the image doesn't load, the browser will show this text instead.

### **c) `width` and `height` – Adjusting Image Size**
- You can set how big or small the image should be.  

**Example:**  
```html
<img src="dog.jpg" alt="A playful dog" width="200" height="150">
```
This makes the image **200 pixels wide** and **150 pixels tall**.

### **d) `title` – Tooltip on Hover**
- The `title` attribute shows text when you hover over the image.  

**Example:**  
```html
<img src="bird.jpg" alt="A blue bird" title="This is a blue bird">
```

---

## **3. Fun Activity: Adding an Image to a Webpage**
Let’s create a simple webpage with an image of a cat!  

### **Try This Code:**
```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Image</title>
</head>
<body>
    <h1>Look at This Cute Cat!</h1>
    <img src="cat.jpg" alt="A fluffy white cat" width="300">
</body>
</html>
```

- Save this as `index.html` and place a cat image in the same folder as your file.  
- Open it in a browser, and you will see your cat picture on the webpage!  

---

## **4. Why is the `<img>` Tag Important?**
- It makes websites more **attractive and engaging**.  
- Helps people **understand content visually**.  
- Can be used for **logos, icons, and backgrounds**.  

---

## **Conclusion**
The `<img>` tag is a powerful tool to add images to websites. Just remember:  
✅ Use **`src`** to tell where the image is from.  
✅ Use **`alt`** for a description.  
✅ Adjust **`width` and `height`** to fit your design.  

Now, go ahead and add some pictures to your webpage! What image will you add first?
