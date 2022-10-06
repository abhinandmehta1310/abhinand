# abhinand
my first project built using HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <title>abhinand web</title>
    <link rel="shortcut icon" href="C:\Users\HP\Desktop\HTML\favicon_io\favicon.ico" type="image/x-icon">

</head>
<body style="background-color: royalblue">
    <h1>DRINKS</h1>
    <!-- we should not use this type attribute as it comes under css -->
    <ul type = "square">
        <li>MOUNTAIN DEW</li>
        <li>COCA COLA</li>
        <LI>PEPSI
        </LI>
        <LI>MARINDA</LI>
        <LI>THUMS UP</LI>

    </ul>
    <h1>DRINKS</h1>
    <ol type="I">
        <li>MOUNTAIN DEW</li>
        <li>COCA COLA</li>
        <LI>PEPSI
        </LI>
        <LI>MARINDA</LI>
        <LI>THUMS UP</LI>
    </ol>
    <table border="1px">
        <caption>LIST OF PLAYERS AND THEIR SCORES</caption>
        <tr>
            <thead>
                <th>SR NO.</th>
                <th>NAME</th>
                <TH>AGE</TH>
                <TH>BEST SCORE</TH>
                <TH>FORMAT</TH>
                <TH>ACHIVEMENTS</TH>
                <th>about</th>
            </thead>
        </tr>
        <tbody>
            <tr>
            <td>1</td>
            <td>Sachin Tendulkar</td>
            <td>49</td>
            <td>248</td>
            <td>Test</td>
            <td>World Cup</td>
            <td><a href="https://en.wikipedia.org/wiki/Sachin_Tendulkar" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/SachinTendulkar3.jpg/330px-SachinTendulkar3.jpg" alt="error" width="120"></a></td>
            </tr>
            <tr>
                <td>2</td>
            <td>MS Dhoni</td>
            <td>41</td>
            <td>224</td>
            <td>Test</td>
            <td>World Cup</td>
            <td><a href="https://www.cricbuzz.com/profiles/265/ms-dhoni" ><img src="https://www.cricbuzz.com/a/img/v1/152x152/i1/c170677/ms-dhoni.jpg" alt="error" width="120"></a></td>
            </tr>
            <tr>
                <td>3</td>
                <td>Virat Kohli</td>
                <td>33</td>
                <td>254</td>
                <td>Test</td>
                <td>Meme Content</td>
                <td><a href="https://www.cricbuzz.com/profiles/1413/virat-kohli" ><img src="https://www.cricbuzz.com/a/img/v1/152x152/i1/c170661/virat-kohli.jpg" alt="error" width="120"></a></td>
            </tr>

        </tbody>

    </table>
    <div>
        <H1> HAVE YOU COMPLETE YOUR WORK</H1>
        <form action="form.php">
            <input type="text" placeholder="ENTER YOUR NAME"><BR>
                <label for="sectionida">
                    <input type="radio" name="section" id="sectionida">YES <br>
                </label>
                <label for="sectionidb">
                    <input type="radio" name="section" id="sectionidb">NO <br>
                </label>
        </form>
                <textarea name="" id="" cols="30" rows="10" placeholder="reason"></textarea>
               <select name="STREAM" id="STREAM">
               <option value="SELECT YOUR STREAM">SELECT YOUR STREAM</option>
            <option value="BTECH">BTECH</option>
            <option value="BCA">BCA</option>
            <option value="BBA">BBA</option>
            <option value="MBA">MBA</option>
            <option value="B.PHARMACY">B.PHARMACY</option>
               </select>

     
    </div>
    <div>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/9W4leiTZDz4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div>
        <video src="C:\Users\HP\Desktop\HTML\K.G.F.2022.v3.720p.CAMRip.HINDI.DUB.1XBET.mp4" autoplay controls width="880px"></video>
    </div>
</body>
</html>
