#NETFLIX Clone Using HTML and CSS:-

###HTML code:

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.3.0/fonts/remixicon.css" rel="stylesheet" />
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="main">
        <div class="box"></div>
        <nav>
            <span><img src="assets for netflix/logo/logo.svg"></span>
            <div>
                <button class="btn">English</button>
                <button class="btn btn-red-sm">Sign In</button>
            </div>
        </nav>
        <div class="hero">
            <span>Enjoy big movies,hit series and more from ₹ 149.</span>
            <span>Join today.Cancel anytime.</span>
            <span>Ready to watch?Enter your email to create or restart your membership.</span>
            <div><input type="text" placeholder="Email Adress">
                <button class="btn btn-red">Get Started &gt;</button>
            </div>
        </div>

        
    </div>
    <div class="separation"></div>

    <section class="trending">
        <div id="header"><p>Trending</p></div>
        <div class="childs">

            <div class="btns" >
                <p >India</p>
                <i class="ri-arrow-down-s-fill"></i>
            </div>
            <div class="btns">
                <p>Movies</p>
                <i class="ri-arrow-down-s-fill"></i>
            </div>
        </div>
    </section>
    <section class="first">

        <div>
            <span>Enjoy on your TV</span>
            <span>Watch on smart TVs,PlayStation,Xbox,Chromecast,Apple TV,Blue-ray Players and more.</span>
        </div>
        <div class="secImg">

            <video src="assets for netflix/Cinema.mp4/Cinema.mp4.mp4" controls autoplay loop muted>

            </video>
        </div>
    </section>
    <div class="separation"></div>
    <section class="first1">
        <div class="Img1">
            <img src="assets for netflix/image 1/image2.jpeg">
        </div>
        <div>
            <span>Download your shows to watch offline</span>
            <span>Save your favourites easily and always have something to watch.</span>
        </div>

    </section>
    <div class="separation"></div>
    <section class="first2">
        <div>
            <span>Watch everywhere</span>
            <span>Stream unlimited movies and TV shows on your phone,tablet,laptopand TV.</span>
        </div>
        <div class="Img2">
            <img src="assets for netflix/image 1/image.1.jpg">

        </div>
    </section>
    <div class="separation"></div>
    <section class="first3">
        <div class="Img3">

            <video src="assets for netflix/Doraemon.mp4/Doraemon.mp4 - Copy.mp4" controls autoplay loop muted></video>
        </div>
        <div>
            <span>Create profiles for kids</span>
            <span>Send children on adventures with their favourite characters in a space made just for them-free with
                your membership.</span>
        </div>

    </section>
    <div class="separation"></div>



</body>

</html>

###CSS code:

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

body,
html {
    background-color: black;
    height: 100vh;
    width: 100vw;

}


.main {
    background-image: url("assets for netflix/image3/netflix.background image.jpg");
    height: 70vh;
    background-position: center center;
    background-size: max(1200px, 100vw);
    background-repeat: no-repeat;
    position: relative;
}

.box {
    height: 70vh;
    width: 100vw;
    opacity: 0.67;
    position: absolute;
    top: 0;
    background-color: black;
}

nav {
    max-width: 80vw;
    margin: auto;
    display: flex;
    align-items: center;
    height: 62px;
    justify-content: space-between;
}

nav img {
    color: red;
    width: 140px;
    position: relative;
    z-index: 10;
}

nav button {
    position: relative;
    z-index: 10;
}


.hero {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    flex-direction: column;
    position: relative;
    gap: 19px;
    padding: 0 30px;

}

.hero> :nth-child(1) {
    font-weight: bolder;
    font-size: 55px;
    text-align: center;
}

.hero> :nth-child(2) {
    font-weight: 400;
    font-size: 23px;
    text-align: center;
}

.hero> :nth-child(3) {
    font-weight: 400;
    font-size: 23px;
    text-align: center;
}

.separation {
    height: 2px;
    position: relative;
    background-color: black;

}

.main.button {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 16px;
}

.btn {
    padding: 7px 30px;
    font-weight: 700;
    background-color: rgba(23, 23, 23, 0.7);
    color: white;
    border-radius: 4px;

}

.btn-red {
    background-color: red;
    color: white;
    padding: 9px 35px;
    font-size: 20px;
    border-radius: 4px;
    margin-left: 4px;
    font-weight: bold;


}

.btn-red-sm {
    background-color: red;
    color: white;
    padding: 7px 13px;
    font-weight: 700;
    margin-left: 7px;
    border-radius: 4px;

}

.main input {
    background-color: rgba(23, 23, 23, 0.7);
    padding: 10px 111px 12px 20px;
    color: white;
    font-size: 12px;
    border-radius: 4px;
    border: 1px solid rgba(23, 23, 23, 0.5);
}
section.trending{
    height: 15vh;
    max-width: 80vw;
    display: flex;
    flex-direction: column;
    box-sizing: border-box;
    margin-left: 200px;
}
#header{
    color:white;
    font-size: 30px;
    font-weight:900;
    margin-top: 20px;
    margin-bottom: 20px;
}
.childs{
    display: flex;
    font-size: 20px;
    font-weight: 700;
    color:white;
    gap: 0 20px;
    

}
.btns {
    border: 2px solid white;
    padding: 9px 15px;
    display: flex;
    justify-content: baseline;
    text-align: center;
    border-radius: 4px;
    align-items: center;
    
}    
    
section {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

section.first {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 50vh;
    color: white;
}

.secImg {
    position: relative;


}
.secImg video {
    width: 590px;
    height: 350px;
    z-index: 2;
    padding-top: 60px;
    padding-right: 200px;
}

section.first>div {
    display: flex;
    flex-direction: column;

}

section.first>div :nth-child(1) {
    font-size: 40px;
    font-weight: bolder;
    padding-left: 200px;




}

section.first>div :nth-child(2) {
    font-size: 23px;
    padding-left: 200px;




}

section.first1 {
    display: flex;
    align-items: center;
    height: 40vh;
    margin: auto;
    color: white;
    justify-content: center;
}

.Img1 {
    height: 300px;
    width: 400px;
    padding-right: 65px;
    padding-top: 30px;
}

section.first2 {
    display: flex;
    align-items: center;
    height: 40vh;
    margin: auto;
    color: white;
    justify-content: center;
}

.Img2 {

    height: 320px;
    width: 360px;
    padding-left: 60px;

}

section.first3 {
    display: flex;
    align-items: center;
    max-width: 80vw;
    height: 40vh;
    margin: auto;
    color: white;
    justify-content: space-between;
}

.Img3 {

    width: 320px;
    height: 550px;
    z-index: 2;
    padding-top: 220px;
    padding-bottom: 630px;



}

section.first1>div {
    display: flex;
    flex-direction: column;


}

section.first1>div :nth-child(1) {
    font-size: 40px;
    font-weight: bolder;
    padding-left: 95px;
    padding-right: 70px;

}

section.first1>div :nth-child(2) {
    font-size: 23px;
    padding-left: 95px;
    padding-bottom: 15px;

}

section.first2>div {
    display: flex;
    flex-direction: column;


}

section.first2>div :nth-child(1) {
    font-size: 40px;
    font-weight: bolder;
    padding-top: 40px;
    padding-right: 60px;
}

section.first2>div :nth-child(2) {
    font-size: 23px;
    padding-right: 60px;
}

section.first3>div {
    display: flex;
    flex-direction: column;


}

section.first3>div :nth-child(1) {
    font-size: 40px;
    font-weight: bolder;
    padding-top: 60px;
    padding-right: 60px;
    padding-left: 95px;


}

section.first3>div :nth-child(2) {
    font-size: 23px;
    padding-left: 95px;
    padding-bottom: 60px;

}





