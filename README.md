# Ex.05 Design a Website for Server Side Processing
# Date:
# AIM:
To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side.

# FORMULA:
P = I2R
P --> Power (in watts)
 I --> Intensity
 R --> Resistance

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Create python programs for views and urls to perform server side processing.

## Step 5:
Create a HTML file to implement form based input and output.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
math.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Power Calculator</title>
</head>
<style>
    .one{
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        color: aliceblue;
        background-color: black;
    }
</style>
<body>
    <div>
        <center><div class="one"><h1>POWER CALCULATOR</h1></div>
            <form align="center" method="POST">
                {% csrf_token %}
                Intensity <input name="I" value="{{i}}">
                <br>
                <br>
                Resistance <input name="R" value="{{r}}">
                <br>
                <br>
                <input type="submit" value="calculate">
                <br>
                <br>
                Power <input name="power"value={{power}}>
            </form>
        </center>
    </div>
</body>
</html>
```
# SERVER SIDE PROCESSING:
![alt text](<Screenshot 2024-12-06 204828.png>)
# HOMEPAGE:
![alt text](<Screenshot 2024-12-06 205025.png>)
# RESULT:
The program for performing server side processing is completed successfully.
