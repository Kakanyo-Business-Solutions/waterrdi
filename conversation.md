## Generate an HTML & CSS landing page with source code based on the design image below:

Sure, here is the HTML and CSS code for a landing page based on the image you described:

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>South Africa's Water RDI Roadmap</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="header-top">
                <div class="logo">
                    <img src="logo.png" alt="South Africa Department of Science and Technology Logo">
                </div>
                <div class="department-title">
                    <h1>WATER & SANITATION</h1>
                    <h1>SCIENCE & TECHNOLOGY</h1>
                </div>
            </div>
            <div class="header-bottom">
                <div class="department">
                    <h2>Department of Science and Technology</h2>
                    <h3>Republic of South Africa</h3>
                </div>
                <div class="commission">
                    <h2>Water Research Commission</h2>
                </div>
            </div>
        </div>
    </header>
    <main>
        <div class="container">
            <div class="title">
                <h1>SOUTH AFRICA'S WATER RESEARCH, DEVELOPMENT AND INNOVATION (RDI) ROADMAP: 2015-2025</h1>
            </div>
            <div class="description">
                <p>The Water Research, Development and Innovation (RDI) Roadmap is a high-level planning intervention that facilitates and guides refocusing of research, reprioritisation of funds, synergising of existing initiatives and ring-fencing of new resources to facilitate a more optimal water innovation system.</p>
            </div>
            <div class="pillars">
                <h3>INNOVATION</h3>
                <h3>RESEARCH</h3>
                <h3>CAPACITY</h3>
            </div>
            <div class="under-construction">
                <p>The official Water RDI Roadmap is currently under reconstruction</p>
                <h2>COMING SOON</h2>
            </div>
            <div class="contact">
                <h3>Sarah Ravhudzulo</h3>
                <h3>Water RDI Roadmap Coordinator</h3>
                <p>Email: Sarahr@wrc.org.za;</p>
                <p>Tel: +27 12 761 9300</p>
            </div>
        </div>
    </main>
</body>
</html>
```

**style.css**

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

.container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background-color: #3274c0;
    color: #fff;
}

.header-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo img {
    width: 150px;
    height: auto;
}

.department-title {
    text-align: center;
}

h1,
h2,
h3 {
    margin: 0;
    padding: 0;
}

.header-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 20px;
}

.commission {
    text-align: right;
}

main {
    padding-top: 40px;
}

.title {
    text-align: center;
}

.description {
    text-align: center;
    padding-top: 20px;
    line-height: 1.5;
}

.pillars {
    display: flex;
    justify-content: center;
    padding-top: 40px;
}

.pillars h3 {
    margin: 0 20px;
}

.under-construction {
    text-align: center;
    padding-top: 40px;
}

.under-construction p {
    font-style: italic;
}

.contact {
    text-align: center

```
Sources:
1. https://medium.com/samsung-internet-dev/making-an-ar-game-with-aframe-529e03ae90cb
2. https://wrc.org.za/?mdocs-file=62744
3. https://www.wrc.org.za/wp-content/uploads/mdocs/TT%20865-4-21%20final%20web.pdf