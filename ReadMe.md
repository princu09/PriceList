## Heaven CSS Layout Free Source Code By NorthFox Developers

##### 📫 Connect with me here:<br />
 <br />
 <p>
  <a target="_blank" href="https://www.instagram.com/princu.09">
    <img src="https://img.shields.io/badge/princu.09-386938188?style=flat&logo=instagram&color=black">
  </a> &nbsp; 
  <a target="_blank" href="https://twitter.com/princu09">
    <img src="https://img.shields.io/badge/@princu09-30302f?style=flat&logo=twitter&color=black">
  </a>&nbsp; 
  <a target="_blank" href="https://github.com/princu09">
    <img src="https://img.shields.io/badge/@princu09-30302f?style=flat&logo=github&color=black">
  </a>&nbsp;
    <a target="_blank" href="https://www.t.me/proghub09">
    <img src="https://img.shields.io/badge/ProgHub09-386938188?style=flat&logo=telegram&color=black">
  </a>
</p>


![Video Here](https://github.com/princu09/PriceList/blob/master/PriceList.gif?raw=true)


#### HTML File

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="https://princu09.github.io/nfwebbuilder/img/logo.png" type="image/png" sizes="16x16">
    <title>Price Card</title>
</head>

<body>
    <div class="header">
        <h1>Price List</h1>
        <h3>NorthFox Developers</h3>
    </div>

    <div class="container">
        <div class="card">
            <div class="card-image">
            </div>
            <div class="card-text">
                <h2>Basic</h2>
                <div class="list">
                    <li>Create Static Website</li>
                    <li>Domail .store , .online , etc..</li>
                    <li>According to your need</li>
                    <li>Free Cloudflare SSL</li>
                    <li>Ready In 2-3 Days</li>
                </div>
            </div>
            <div class="card-stats">
                <div class="stat">
                    <div class="value">3K</div>
                    <div class="type">Price</div>
                </div>
                <div class="stat border">
                    <div class="value">1-3</div>
                    <div class="type">Days</div>
                </div>
                <div class="stat">
                    <div class="value">No</div>
                    <div class="type">Database</div>
                </div>
            </div>
        </div>

        <div class="card">
            <div class="card-image2"></div>
            <div class="card-text">
                <h2>Standard</h2>
                <div class="list">
                    <li>Create Static Website</li>
                    <li>Best 1 Year domain Free</li>
                    <li>According to your need</li>
                    <li>Free Cloudflare SSL</li>
                    <li>Ready In 1-2 hours</li>
                </div>
            </div>
            <div class="card-stats">
                <div class="stat">
                    <div class="value">5K</div>
                    <div class="type">Price</div>
                </div>
                <div class="stat border">
                    <div class="value">1-3</div>
                    <div class="type">Hours</div>
                </div>
                <div class="stat">
                    <div class="value">No</div>
                    <div class="type">Database</div>
                </div>
            </div>
        </div>
        <div class="card">
            <div class="card-image3"></div>
            <div class="card-text">
                <h2>Premium</h2>
                <div class="list">
                    <li>Wordpress, Python Website</li>
                    <li>Free Domain as you like</li>
                    <li>Free Hosting with Database</li>
                    <li>Free Cloudflare SSL</li>
                    <li>Ready like a website</li>
                </div>
            </div>
            <div class="card-stats">
                <div class="stat">
                    <div class="value">25K</div>
                    <div class="type">Read</div>
                </div>
                <div class="stat border">
                    <div class="value">No</div>
                    <div class="type">Fix Time</div>
                </div>
                <div class="stat">
                    <div class="value">1</div>
                    <div class="type">Database</div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>
```

#### CSS File

```
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');
* {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
}

html {
    scroll-behavior: smooth;
}


/* Created By NorthFox Group */

body {
    width: 100vw;
    height: 100vh;
    align-items: center;
    justify-content: center;
    background: url('https://images.unsplash.com/photo-1461301214746-1e109215d6d3?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
}

.container {
    position: relative;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.card {
    margin: 50px 20px;
    display: grid;
    grid-template-columns: 300px;
    grid-template-rows: 210px 250px 60px;
    grid-template-areas: "image" "text" "stats";
    border-radius: 18px;
    background: white;
    box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.9);
    text-align: center;
    transition: 0.5s ease;
    cursor: pointer;
}

.card-image {
    grid-area: image;
    background: url('https://images.unsplash.com/photo-1455894127589-22f75500213a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1279&q=80');
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
    background-size: cover;
}

.card-image2 {
    grid-area: image;
    background: url('https://images.unsplash.com/photo-1480506132288-68f7705954bd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1393&q=80');
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
    background-size: cover;
    background-position: center;
}

.card-image3 {
    grid-area: image;
    background: url('python.jpg');
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
    background-size: cover;
    background-position: center;
}

.card-text {
    grid-area: text;
    margin: 35px 0px;
}

.list {
    justify-content: center;
    align-items: center;
    position: relative;
    display: inline-block;
}

.card-text li {
    margin-top: 10px;
    color: grey;
    font-size: 13px;
    font-weight: 300;
    text-align: left;
}

.card-text h2 {
    margin-top: 0px;
    font-size: 20px;
    font-weight: 600;
}

.card-stats {
    grid-area: stats;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr;
    border-bottom-left-radius: 15px;
    border-bottom-right-radius: 15px;
    background: orange;
}

.card-stats .stat {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    color: white;
}

.card-stats .type {
    font-size: 11px;
    font-weight: 600;
    text-transform: uppercase;
}

.card-stats .value {
    font-size: 22px;
    font-weight: 500;
}

.card-stats .border {
    border-left: 1px solid darkorange;
    border-right: 1px solid darkorange;
}

.card:hover {
    transform: scale(1.2);
    box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.6);
}

.header h1 {
    color: #fff;
    position: absolute;
    top: 15%;
    left: 50%;
    font-weight: 600;
    font-size: 30px;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
}

.header h3 {
    font-weight: 600;
    letter-spacing: 5px;
    color: #fff;
    font-size: 15px;
    position: absolute;
    top: 18%;
    left: 50%;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
}

.footer h6 {
    font-weight: 600;
    letter-spacing: 5px;
    color: #fff;
    font-size: 15px;
    position: absolute;
    bottom: 10%;
    left: 50%;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
}

@media(max-width:1110px) {
    .header {
        margin-bottom: 120px;
    }
    .header h1 {
        top: 10%;
        left: 50%;
        font-weight: 600;
        font-size: 40px;
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }
    .header h3 {
        font-weight: 600;
        letter-spacing: 5px;
        color: #fff;
        font-size: 12px;
        position: absolute;
        top: 14%;
        left: 50%;
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }
}

@media(max-width:400px) {
    .header h1 {
        color: #fff;
        position: absolute;
        top: 10%;
        left: 50%;
        font-size: 30px;
        letter-spacing: 2px;
        font-weight: 600;
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }
    .header h3 {
        font-weight: 600;
        letter-spacing: 1px;
        color: #fff;
        font-size: 12px;
        position: absolute;
        top: 13%;
        left: 50%;
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }
}
```
