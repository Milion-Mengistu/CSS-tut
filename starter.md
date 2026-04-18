Here’s a simple set of starter files you can use to teach CSS hands-on. They’re minimal but structured so learners can experiment with each concept from your PDF.

---

### 📄 index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CSS Practice</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Welcome to CSS Basics</h1>
  <p class="intro">This is a starter file for practicing CSS.</p>

  <div class="box">Box Model Example</div>

  <div class="flex-container">
    <div class="flex-item">Flex 1</div>
    <div class="flex-item">Flex 2</div>
    <div class="flex-item">Flex 3</div>
  </div>

  <div class="grid-container">
    <div class="grid-item">Grid 1</div>
    <div class="grid-item">Grid 2</div>
    <div class="grid-item">Grid 3</div>
    <div class="grid-item">Grid 4</div>
  </div>
</body>
</html>

---

### 🎨 style.css
/* Text styling */
h1 {
  font-family: Arial, sans-serif;
  color: darkblue;
  text-align: center;
}

.intro {
  font-size: 18px;
  color: gray;
}

/* Box model */
.box {
  width: 200px;
  padding: 20px;
  border: 5px solid black;
  margin: 15px auto;
  text-align: center;
}

/* Flexbox */
.flex-container {
  display: flex;
  justify-content: space-around;
  margin: 20px;
}

.flex-item {
  background-color: lightcoral;
  padding: 10px;
  flex: 1;
  margin: 5px;
  text-align: center;
}

/* Grid */
.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 10px;
  margin: 20px;
}

.grid-item {
  background-color: lightgreen;
  padding: 20px;
  text-align: center;
}

---

### 🚀 How to Use in Class
- Step 1: Open index.html in a browser and show the default look.  
- Step 2: Modify CSS live (e.g., change colors, adjust margins) and let students see the effect.  
- Step 3: Assign mini tasks like “make the box red,” “center the flex items,” or “add a third column to the grid.”  

This way, learners can immediately connect the theory from your slides with practical results.

Would you like me to also create a progressive exercise sheet (like a checklist of challenges) that matches each CSS topic in your PDF, so students can follow along step by step?
