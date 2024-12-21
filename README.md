# Ex.08 Design of Interactive Image Gallery
## Date:21/12/2024

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
    <style>
        body {
            font-family:cursive;
            background-color:rgb(32, 28, 28);
            display:flex;
            justify-content: center;
            align-items: center;
            margin: 0;
            flex-direction: column;
            
        }
        .photo-container {
            text-align: center;
            color:bisque;
            font-size:medium;
        }

        .photo {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px; 
        }

        .photo-item {
            width: 350px; 
            height:500px;
                }
        footer {
            text-align: center;
            font-size: 25px;
            background-color:antiquewhite;
            margin-top: 250px; 
            color:darkred;
        }

    </style>
</head>
<body>
    <div class="photo-container">
        <h1 >GALLERY OF CRICKETERS</h1>
        <div class="photo">
            <img src="dhoni.jpg" alt="Image 1" class="photo-item" id="my_image" onmouseover="zoomIn()" onmouseout="zoomOut()">
            <img src="rishab.jpg" alt="Image 2" class="photo-item">
            <img src="Suresh-Raina-best-performances-in-T20s.jpg" alt="Image 3" class="photo-item">
            <img src="hardhik.jpg" alt="Image 4" class="photo-item">
            <img src="thivatiya.jpg" alt="Image 5" class="photo-item">
            
        </div>
        <footer>
            Designed and developed by Nikila &copy 2024
        </footer>
    </div>
    <script> 
    function zoomIn() { 
      document.getElementById("my_image").style.width = "600px";
      document.getElementById("my_image").style.height = "700px";

    } 
    function zoomOut() { 
      document.getElementById("my_image").style.width = "350px"; 
      document.getElementById("my_image").style.height = "500px";
      

    } 
    </script>
</body>
</html>



```

## OUTPUT:
![alt text](<Screenshot (122).png>)
![alt text](<Screenshot (123).png>)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
