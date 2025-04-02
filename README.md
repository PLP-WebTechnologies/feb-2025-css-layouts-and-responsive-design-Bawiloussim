# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>W3_assegnment</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="bawi">
        <ul class="navbar">
            <li>Welcome</li>
            <li>Services</li>
            <li>Contacts</li>
        </ul>
    </nav>
    <h1>THIS IS MY ASSEGNMENT FOR THE WEAK 4</h1>
    <div class="container">
        <p id="weak1">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Non, repudiandae. Re
            consectetur, asperiores, pariatur necessitatibus aliquid ratione 
           reiciendis veritatis architecto, eligendi facere placeat fuga nihil labore eum. Unde, debitis sunt!</p>
           <p class="bg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus neque 
            quaerat aliquam modi error quasi qui labore? Error id quo laborum. Quod voluptate
             facere natus omnis eos, nostrum suscipit nulla.</p>
    </div>
    <div><img src="3.jpg" alt="image"  class="benja" srcset="3.jpg 1200W, 3.jpg 768w, 3.jpg 546w" sizes="(max-width: 768px) 100vw , 50vw">
        <img src="pc1.jpg" alt="image 2"  class="benja">
    </div>
    
    
</body>
</html>



.navbar{
    list-style-type: none;
    padding: 10;
    display: flex grid;
    gap: 500px;
    place-items: center;

}

li{
    display: inline;
    margin: 150px;
    font-size: 20px;
    font-family: sans-serif;
    display: inline;
}

.bawi{
    background-color: rgb(255, 0, 89);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10vh;
    display: grid;
    @media (max-width: 480px){
        width: 100%;
    }
}

.container{
    display: grid inline;
    grid-auto-columns: auto;
    
}


body{
    background-color: rgb(201, 239, 239);
    margin: 20px ;
}
h1{
    text-align: center;
    background-color: blue;
}

.bg{
    text-align: center;
    -ms-text-size-adjust: auto;
    font-size: medium;
    font-family: sans-serif;
}

img {
    width: 500px;
    height: 400px;
    object-fit: cover;  
    
}

div{
    text-align: center;
    padding: auto;
}

.benja{
    border-radius: 10px;
}
#weak1 {
    color: rgb(192, 189, 134);
    font-size: 20px;
    font-family: sans-serif;
}



