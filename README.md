#Building a Stylish QR Code Page with HTML and CSS**

Are you looking to enhance your frontend development skills by working on practical projects? In this step-by-step guide, we'll walk you through creating a modern QR code display page using HTML and CSS. By following along, you'll not only learn how to structure an HTML document but also apply CSS styling to create an attractive and responsive design.

**Step 1: Setting Up the HTML Structure**

Start by creating a new HTML file and defining the basic structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Add necessary meta tags for better device compatibility -->
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Outfit">
  <!-- Include Google Fonts for a stylish typography -->
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <!-- Link to your favicon -->
  <link rel="stylesheet" href="css/styles.css">
  <!-- Link your CSS stylesheet -->
  <title>QR Code Redesigned</title>
</head>
<body>
  <main>
    <!-- Your content will go here -->
  </main>
</body>
</html>
```

**Step 2: Creating the Card Section**

Within the `<main>` tag, add the following code to create the card section:

```html
<section class="card">
  <img src="images/image.png" id="qr" alt="image of qr code">
  <img src="images/logo.jpg" id="logo" alt="logo here">
  <h1>Improve your frontend skills by building projects</h1>
  
  <div class="upi">
    <img src="images/upi-icon.png" style="height: 40px;">
    <img src="images/paytm-icon.png"  style="height: 20px;">
    <img src="images/phonepe-logo-icon.png"  style="height: 20px;">
    <img src="images/google-pay-icon.png"  style="height: 20px;">
  </div>
  
  <div class="container">
    <p>scan the QR code to</p><img src="images/bmc-logo.svg">
  </div>
  
  <div class="attribution">
    Coded by <a href="https://github.com/developerrahulofficial">Rahul Sahni</a>
  </div>
</section>
```

**Step 3: Applying CSS Styling**

Now, let's add the CSS styling to achieve the desired design. Create a file named `styles.css` in a directory named `css` and add the following CSS code:

```css
/* styles.css */

body {
  align-items: center;
  background-color: hsl(212, 45%, 89%);
  display: flex;
  font-family: "Outfit", serif;
  justify-content: center;
  height: 100%;
  min-height: 100vh;
  overflow: hidden;
  width: 100%;
}

.card {
  background-color: white;
  border-radius: 15px;
  box-shadow: 0 10px 40px hsl(220, 15%, 55%);
  padding: 4%;
  top: 25%;
  text-align: center;
  width: 375px;
}

#qr {
  border-radius: 15px;
  height: 375px;
  width: 375px;
}

#logo {
  height: 10%;
  width: 50%;
  margin-top: 20px;
}

.upi {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

.upi > img {
  padding: 5px;
}

h1 {
  color: hsl(218, 44%, 22%);
  font-weight: 700;
}

p {
  color: hsl(220, 15%, 55%);
  font-size: 15px;
  font-weight: 400;
  padding: 15px;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.attribution {
  font-size: 11px;
  text-align: center;
}

.attribution a {
  color: hsl(228, 45%, 44%);
  text-decoration: none;
}
```

**Step 4: Final Result**

By following these steps, you've successfully created an elegant QR code display page using HTML and CSS. The page features a centered card with a QR code, logo, title, payment icons, a scan message, and attribution. You've also styled it with modern and appealing CSS properties.

Feel free to customize the images, colors, and sizes to match your preferences. As you continue to experiment and learn, you can enhance the page further with additional features and responsive design techniques. Happy coding!
