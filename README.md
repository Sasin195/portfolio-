<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

    <header>
        <h1>Welcome to My Portfolio</h1>
        <a href=""><button>About</button></a>
        <a href=""><button>Skills</button></a>
        <a href=""><button>Projects</button></a>
        <a href=""><button>Contact</button></a>
    </header> 
    <main>

    <section id="about">
        <h2>Sasi NSRIET</h2>
        <img src="DP.jpg" alt="sasi picture" width="300" height="300" border="2">
        <p>
        I am a passionate <b>Web developer</b> with a focus on front-end technologies. <br>
        I am currently Pursuing my <em>B. Tech in NSRIET.</em> <br>
        You can <b>Click here</b> to Checkout What I have learnt in HTML CSS JS
        </p>
    </section>


    <section id="skills">
            <h2>My skills</h2>
        <ol>
            <li>Phython basics</li>
            <li>HTML basics</li>
            <li>JS basics</li>
        </ol>
    </section>

    <section id="projects">
        <h2>My projects</h2>
        <table border="1" cellspacing="3" cellpadding="5">
            <tr>
                <th>Project</th>
                <th>Description</th>
            </tr>
            <tr>
                <td>Portfolio website</td>
                <td>I have built a Portfolio website by using HTML, CSS & JavaScript
                </td>
            </tr>
            <tr>
                <td>Discord Server</td>
                <td>I have maintained many discord server with the help of bots</td>
            </tr>
        </table>
    </section>

    <section id="contact">
    <h2>Contact me</h2>
    <p>Feel free to get in touch with me using the form below:</p>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name">
        <br>
        <label for="email">Email:</label>
        <input type="email" name="email" id="email">
        <br>
        <b>Choose your gender:</b>
        <label for="male">Male</label>
        <input type="radio" name="male" id="male" value="male">
        <label for="female">Female</label>
        <input type="radio" name="female" id="female" value="female">
        <br>
        <b>Select your skill:</b>
        <label for="skill">Web devlopment</label>
        <input type="checkbox" name="skill" id="skill" value="web devlopment">
        <label for="dsa">DSA</label>
        <input type="checkbox" name="dsa" id="dsa" value="dsa">
        <br>
        <label for="bio">Bio (up to 200 characters):</label>
        <input type="text" max="200">
        <br>
        <button>Submit</button>
        <button type="reset">Reset</button>
    <section>
    </main>
    </body>
    <footer>
        <p>© 2024 My Portfolio</p>
    </footer>
</html>
