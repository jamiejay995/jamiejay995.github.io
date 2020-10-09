<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About Me</title>
    <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
 <div class="container">
     <div class="nav-wrapper">
         <div class="left-side">
            <div class="nav-link-wrapper active-nav-link">
                <a href="index.html">Home</a>
            </div>
            
            <div class="nav-link-wrapper">
                <a href="about.html">About</a>
            </div>    
         </div>
         
         <div class="right-class">
             <div class="brand">
                <div>Jamie Jabouri</div>
             </div>
         </div>
     </div>

     <div class="content-wrapper">
         <div class="portoflio-items-wrapper">
         
            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio1.jpg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/quip.png">
                    </div>

                    <div class="subtitle">
                        Learing how to code is fun
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio2.jpg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/crondose.png">
                    </div>

                    <div class="subtitle">
                        This is cool
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio3.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/dailysmarty.png">
                    </div>

                    <div class="subtitle">
                        i should have done this as a career 
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio4.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/dashtrack.png">
                    </div>

                    <div class="subtitle">
                        Am Hacker man
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio5.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/devcamp.png">
                    </div>

                    <div class="subtitle">
                        Klick is great Arthur
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio6.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/devtrunk.png">
                    </div>

                    <div class="subtitle">
                        I just want a bean bag office
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio7.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/edutechional.png">
                    </div>

                    <div class="subtitle">
                        Ping Pong in the break room 
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio8.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/eventbrite.png">
                    </div>

                    <div class="subtitle">
                        Espresso in my office 
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio9.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/ministry-safe.png">
                    </div>

                    <div class="subtitle">
                        Cats are cool 
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio10.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/open-devos.png">
                    </div>

                    <div class="subtitle">
                        How am i doing 
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio11.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/shop-hacker.png">
                    </div>

                    <div class="subtitle">
                        Please hire me 
                    </div>
                </div>
            </div>

            <div class="portoflio-item-wrapper">
                <div class="portfolio-img-background" style="background-image: url(images/portfolio12.jpeg);"></div>
                
                <div class="img-text-wrapper">
                    <div class="logo-wrapper">
                        <img src="images/logos/toastability.png">
                    </div>

                    <div class="subtitle">
                        Learing how to code is fun
                    </div>
                </div>
            </div>


         
        </div>
     </div>

    </div>

</body>
<script>
    const portfolioItems = document.querySelectorAll('.portoflio-item-wrapper')

    portfolioItems.forEach(portfolioItem => {
        portfolioItem.addEventListener('mouseover', () => {
            portfolioItem.childNodes[1].classList.add('img-darken'); 
        })
        portfolioItem.addEventListener('mouseout', () => {
            portfolioItem.childNodes[1].classList.remove('img-darken'); 
        })
    })
</script>
</html>
