# p409-fe-2-intro-to-css-aishamikhail
p409-fe-2-intro-to-css-aishamikhail created by GitHub Classroom
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets\css\style.css">
    <title>Doc for CSS</title>

</head>
<style>
    body{
        background-color: azure;
    }

</style>
<body>
    <form style="margin-top: 32px" action="#">
        <h1 style="color: seagreen;">Application form</h1>
        
        <label for class="color-royal"> Name</label>
        <input id="Name" type="text" name=Name>
        <br>
        <br>
        <label for class="color-royal">Surname</label>
        <input id="Surname" type="text" name=Surname>
        <br>
        <br>
        <label for class="color-royal">Middle name</label>
        <input id="Middle name" type="text" name=Middlename>
        <hr>
        
        <h5 class="color-indigo">Select your gender</h5>
        <label for="gender-male">Male</label>
        <input id="gender-male" type="radio" name=gender>
        <br>
        <label for="gender-female">Female</label>
        <input id="gender-female" type="radio" name=gender>
        <br>
        <label for="gender-other">Other</label>
        <input id="gender-other" type="radio" name=gender>
        <hr>
    
        <label for>Birth date</label>
        <input id="Birth" type=date name=Birth>
        <hr>

        <label for style="color: green;">Password</label>
        <input style="background-color: green; id="Password" type=Password name=Password>
        <hr>

        <h5 class="color-red">Work Experience</h5>
    
        <label for> <i>(Please choose the start date and end date. If you are still hired leave the end date empty) </i></label>
        <br>
        <br>
        <label for>form</label>
        <input id="Experience" type=date name=Experience>
        <br>
        <label for>to</label>
        <input id="Experience" type=date name=Experience>
        <hr>
    
        <h5 class="color-brown">Choose the education program</h5>
        <i>
        <label for>Fashion Design</label>
        <input id="Choose the education program" type=Checkbox name=program>
        <br>
        <label for>Concept and Styling</label>
        <input id="Choose the education program" type=Checkbox name=program>
        <br>
        <label for>Fashion Management</label>
        <input id="Choose the education program" type=Checkbox name=program>
        <br>
        <label for>Business of Fashion</label>
        <input id="Choose the education program" type=Checkbox name=program>
        </i>
        <hr>
    
        <h5 class="color-brown">Choose the education method</h5>
        <label for="Distance">Distance</label>
        <input id="Distance" type=radio name=method>
        <br>
        <label for="In-campus">In-campus</label> </label>
        <input id="In-campus" type=radio name=method>
        <hr>
    
        <h5>Choose the color of your taste</h5>
        <input id="color" type=color name=color>
        <hr>

        <i>(WARNING: before submitting your application, please make sure that you have filled all sections out, otherwise your application will not be considered)</i>
        <br>
        <br>    
        <input id="Submit" type="submit" name=submit>
        </form>
        
    </body>
    </html>
    
    
    
    
    .color-brown {
    color: brown;
    } 

.color-red {
    color: rgb(110, 5, 5);
}

.color-indigo {
    color: indigo;
}

.color-royal {
    color: rgb(23, 47, 117);
}

* {
    color: rgb(105, 70, 4);
}
