<template>
    <div class="wrapper">
        <div class="main-container">
            <!-- Profile Section -->
            <div class="container-one">
                <div class="profile">
                    <img src="https://scontent.fceb3-1.fna.fbcdn.net/v/t1.15752-9/431580596_1082901819491087_2002995294518706903_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEZmv1c5uNds2k522XwKYdNeEwcuhIwTVZ4TBy6EjBNVvZnfNpS5a4Dcv6bj824hjLLzEjWbVpvg8dnQD3k9m-4&_nc_ohc=49e4B-WvEKYAX-TAe2A&_nc_ht=scontent.fceb3-1.fna&oh=03_AdRbMVLkMUY8_j3IBw48LffMWtMs_IcrE9NsNVkxC4d7zA&oe=662DF236" alt="Stefano Suan Profile Picture">
                    <h3>Stefano Suan</h3>
                    <p>SOFTWARE DEVELOPER</p>
                </div>
                <!-- Social Links -->
                <div class="social-link">
                    <div class="link">
                        <a href="https://github.com/23spetsnaz/stefano.git" target="_blank">
                            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDK3Qt5DVYDOQsN056KUMSmIOC7_XnLTSrIg&usqp=CAU" alt="GitHub">
                            <h2>GITHUB</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/profile.php?id=100006484509650" target="_blank"> 
                            <img src="../assets/facebook.jpg" alt="Facebook">
                            <h2>FACEBOOK</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.instagram.com/23spetsnaz/" target="_blank">
                            <img src="../assets/instagram.jpg" alt="Instagram">
                            <h2>INSTAGRAM</h2>
                        </a>
                    </div>
                </div>
            </div>
            <!-- About Me Section -->
            <div class="container-two">
                <div class="about-me">
                    <h1>About Me</h1>
                    <p>Stefano Suan, a 22-year-old resident of Alegria, Cordova, is an optimistic and resilient software developer.</p>
                    <!-- Language Section -->
                    <div class="language-section">
                        <h1>Technologies Studied</h1>
                        <div class="logos">
                            <img src="../assets/japan.jpg" alt="Japanese">
                            <img src="../assets/english.jpg" alt="English">
                            <img src="../assets/bisaya.jpg" alt="Bisaya">
                        </div>
                        <!-- Contact Section -->
                        <div class="contact-section">
                            <div class="project-button">
                                <a href="tel:09276553374">Contact Number: 09276553374</a>
                            </div>
                            <div class="project-button">
                                <a href="mailto:stefanosuan23@gmail.com">EMAIL: stefanosuan23@gmail.com</a>
                            </div>
                        </div>
                        <a href="c:\Users\DELL i5\Desktop\my resumeeee - Shortcut.lnk">MY Resume</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
}

.wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

img {
    height: 80px;
    border-radius: 50%;
}

/* Main Container Styles */
.main-container {
    display: flex;
    flex-direction: column;
    background-color: #fff;
    border-radius: 30px;
    width: 90%;
    max-width: 800px;
    box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
    padding: 40px;
}

/* Container One Styles */
.container-one {
    background-color: #f1f1f1;
    padding: 30px;
    border-radius: 50px;
    margin-bottom: 30px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
}

.profile img {
    height: 150px;
    border: 5px solid #fff;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
}

.link a {
    text-decoration: none;
    color: #333;
    font-size: 18px;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    transition: 0.3s ease;
}

.link a:hover {
    color: #007bff;
}

.link img {
    height: 50px;
    margin-right: 15px;
    border-radius: 10px;
    transition: 0.3s ease;
}

.link img:hover {
    transform: scale(1.1);
}

/* Container Two Styles */
.container-two {
    background-color: #f1f1f1;
    padding: 30px;
    border-radius: 30px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
}

.about-me {
    text-align: center;
    margin-bottom: 40px;
}

.language-section h1 {
    margin-bottom: 20px;
    font-size: 24px;
    color: #333;
}

.logos img {
    height: 50px;
    margin-right: 15px;
    border-radius: 50%;
    transition: 0.3s ease;
}

.logos img:hover {
    transform: scale(1.1);
}

.contact-section {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.project-button {
    background-color: #007bff;
    color: #fff;
    border-radius: 25px;
    padding: 15px 25px;
    margin: 10px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
    transition: 0.3s ease;
}

.project-button:hover {
    background-color: #0056b3;
}

.project-button a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}
</style>

