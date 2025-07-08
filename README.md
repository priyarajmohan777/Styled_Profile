# Styled_Profile_Card
## Date:08-07-2025

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>My Profile</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
   <article class="prof-card">
    <h1>Priya R</h1>
   
    <h2>Aspiring Web Developer | Exploring Full-Stack & AI</h2>

    <img src="me.jpg" alt="Image Not Found"> <br>
    <hr>

    <article>
        <section>
          <p>Hello! I'm Priya, a third-year Computer Science student passionate about technology, coding, and building impactful projects. I'm currently exploring data science, machine learning, and full-stack development. I love turning ideas into real-world solutions and continuously learning new skills to grow as a developer.</p>
          </section>
    </article>

    <hr>

    <article>
    <h3> Projects </h3>
    <section> <h4>Project 1</h4>
    <p>DigiEffect - Impact of Digital Learning tools on Student Performance</p>
    </section>

    <section> <h4>Project 2</h4>
    <p>BuyWise - Chatbot that gives recommendations for products</p>
    </section>

    </article>
    
    <hr>

    <article>
        <h3>Skills</h3>
    <section>
        
        <ul>
            <li>C++</li>
            <li>Java</li>
            <li>HTML</li>
            <li>CSS</li>
        </ul>
    </section>
    </article>
     
    </article> 
</body>
</html>
```

## CSS Code:
```
body
{
    max-width: 1000px;     
    margin: auto;       
    text-align: center; 
    background-color: #F0F4EF;
    font-family:Arial, Helvetica, sans-serif;
}

img {
    display: block;
    width: 150px;
    height: 200px;
    border-radius: 50%;
    object-fit: fill;
    margin: auto;
}

article
{
    border: 3px solid #9DC08B;
    border-radius: 20px;
    background-color: #F6FFED;
    align-content: center;
    margin-bottom: 20px;
    margin-top: 15px;
    padding: 20px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
}

.prof-card
{
    background-color: #9DC08B;
    padding: 20px;
    margin: 0px 10px;
}

hr {
    border: none;
    height: 2px;
    background-color: #52734D;
    margin: 20px auto;
}

section
{
    background-color: #DDEAC1;
    border-radius: 10px;
    flex-wrap: wrap;
    padding: 10px;
    margin-top: 20px;
}
```
## Output:
![image](https://github.com/user-attachments/assets/8f65b51d-7671-4435-b336-c4783ea354fd)


![image](https://github.com/user-attachments/assets/1bde00d5-0925-4402-81a0-a248e951ea31)


## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
