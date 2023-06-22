# Ex-09 Create a Birthday card using HTML and CSS
## AIM:
To write html & css code to create birthday card.

## PROCEDURE:
### STEP 1:
Create a html code for the birthday card.

### STEP 2:
Make style for the birthday card using css.

### STEP 3:
Link the css with html by link tag

### STEP 4:
Verify the output by running the birthday card in any web browser.
## Program:-
#### Developed By : Kirupanandhan T
#### Register Number : 212221230051
```html


<!DOCTYPE html>
<html>
<head>
	<title>Birthday Card</title>
    <link href='https://fonts.googleapis.com/css?family=Cedarville Cursive' rel='stylesheet'>
    <link rel="stylesheet" href="style.css">

	
</head>

<body style="background-color: #92e1fb; font-family: 'Open Sans', sans-serif; text-align: center; padding: 50px;">
    <div> </div>
	<h1 style="font-size: 150px; color: #ff9d00; text-shadow: 2px 2px 4px #000000; margin-bottom: 0;font-family: 'Cedarville Cursive';font-size: 72px;">Happy Birthday!</h1>
	<h2 style="font-size: 36px; color: #ff6f69; text-shadow: 2px 2px 4px #000000; margin-top: 5px;font-family:cursive ; margin-bottom: 50px;">Wishing you all the best on your special day.</h2>
	<div class="card">
        <img src="dec.jpg" >    
        <img src="dec.jpg" >
		<p style="font-family: 'Times New Roman', Times, serif; font-size: 24px; color: #ff6f69; text-shadow: 1px 1px 2px #000000; ">Make the next birthday you celebrate a special one with personalized birthday cards paired with a hand-picked happy birthday quote or wish that will surely make that special someone’s day a great day.</p>
        <img src="baloon.avif" style="height: 400px;" width="400px;">
        <img src="Cake_New.png" alt="birthday cake" class="img">
        <img src="baloon.avif" style="height: 400px;" width="400px;">
		<br>
		<a href="https://www.google.com/search?q=birthday+wishes&tbm=isch&ved=2ahUKEwj53dSdipz-AhUcJLcAHfIsAUEQ2-cCe.gQIABAA&oq=birthday+wi&gs_lcp=CgNpbWcQARgAMggIABCABBCxAzIICAAQgAQQsQMyCAgAEIAEELEDMggIABCABBCxAzIICAAQgAQQsQMyCAgAEIAEELEDMgUIABCABDIFCAAQgAQyCAgAEIAEELEDMggIABCABBCxAzoECCMQJzoGCAAQBxAeOgYIABAFEB46CggAEIAEELEDEBM6BwgAEIAEEBNQ3AVYwxNgriVoAHAAeACAAZYBiAGGBpIBAzYuMpgBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=2k4yZPmIHZzI3LUP8tmEiAQ&bih=746&biw=1536&rlz=1C1CHBF_enIN1044IN1044#imgrc=Z0waT9S0C_CjRM" class="btn">Celebrate!</a>
	</div>
</body>
</html>

```
```css
.card {
    background-color: white;
    border-radius: 20px;
    padding: 50px;
    margin-top: 50px;
    box-shadow: 2px 2px 4px #000000;
}

.img {
    margin-top: 50px;
}
.btn {
    background-color: #ff6f69;
    border: none;
    color: white;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 24px;
    border-radius: 10px;
    margin-top: 50px;
    box-shadow: 2px 2px 4px #000000;
    cursor: pointer;
    transition: 0.3s;
    
}
.btn:hover{
   
    background-color: #92e1fb;
    
}
```
## Output:-
![image](https://github.com/Kirupanandhan/BirthdayCard/assets/94386222/f3af0d0b-534b-4230-a104-d8b10cd54d30)

## Result:-
html & css code to create birthday card has been created and output has been verified.
