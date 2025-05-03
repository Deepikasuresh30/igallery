# Ex.08 Design of Interactive Image Gallery
## Date: 03.05.2025
## Developed by: Deepika S
## Reg no: 212223230039

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Gallery </title>
  <tittle>Deepika S (212223230039)</tittle>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f2f2f2;
    }
    h1 {
      text-align: center;
      margin-bottom: 30px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      transition: transform 0.2s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <h1>Image Gallery  </h1>
  <h1> Deepika S (212223230039)</h1>
  <div class="gallery">
    <img src="C:\Users\admin\Downloads\image1.jpg" alt="Image 1">
    <img src="C:\Users\admin\Downloads\image2.jpg" alt="Image 2">
    <img src="C:\Users\admin\Downloads\image3.jpg" alt="Image 3">
    <img src="C:\Users\admin\Downloads\image4.jpg" alt="Image 4">
    <img src="C:\Users\admin\Downloads\image5.jpg" alt="Image 5">
    <img src="C:\Users\admin\Downloads\image6.jpg" alt="Image 6">
  </div>

</body>
</html>
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/958b65d8-b574-48ed-9d75-f7e354c968fb)


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
