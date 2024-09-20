# travel-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Booking Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation Section -->
    <header>
        <nav>
            <div class="logo">Tripology</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#offers">Offers</a></li>
                <li><a href="#contact">Bookings	</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section with Slideshow -->
    <section id="home" class="hero">
        <div class="slideshow-container">
            <!-- Slide 1 -->
            <div class="mySlides fade">
                <img src="1st.jpg" style="width:100%">
              
            </div>

            <!-- Slide 2 -->
            <div class="mySlides fade">
                <img src="3rd.jpg" style="width:100%">
          
            </div>

            <!-- Slide 3 -->
            <div class="mySlides fade">
                <img src="paul-pastourmatzis-EXbGG5dBZKw-unsplash.jpg" style="width:100%">
               
            </div>
        </div>
        <br>
        <!-- Dots for Slideshow -->
        <div style="text-align:center">
            <span class="dot"></span>
            <span class="dot"></span>
            <span class="dot"></span>
        </div>

        <div class="hero-content">
            <h1>Explore the World with Tripology</h1>
            <p>Your adventure starts here. Book your dream vacation today!</p>
            <a href="#destinations" class="cta">Explore</a>
        </div>
    </section>


    <section id="destinations" class="travel-spots">
        <h1>Best Travel Spots In India</h1>
        <div class="spots-container">
            <!-- Spot 1: GOA -->
            <div class="spot-card">
                <img src="10.jpg" alt="UAE">
                <div class="spot-info">
                    <div class="country-rating">
                        <span class="country"> GOA</span>
                        <span class="rating">5.0 </span>
                    </div>
                    <div class="price">$200/person</div>
                </div>
                <a href="#" class="more-info">&rarr;</a>
            </div>

            <!-- Spot 2: Singapore -->
            <div class="spot-card">
                <img src="11.jpg" alt="Singapore">
                <div class="spot-info">
                    <div class="country-rating">
                        <span class="country"> Kerala</span>
                        <span class="rating">4.8 </span>
                    </div>
                    <div class="price">$300/person</div>
                </div>
                <a href="#" class="more-info">&rarr;</a>
            </div>

            <!-- Spot 3: New York -->
            <div class="spot-card">
                <img src="12.jpg" alt="New York">
                <div class="spot-info">
                    <div class="country-rating">
                        <span class="country"> Jaipur</span>
                        <span class="rating">5.0 </span>
                    </div>
                    <div class="price">$100/person</div>
                </div>
                <a href="#" class="more-info">&rarr;</a>
            </div>

            <!-- Spot 4: Toronto -->
            <div class="spot-card">
                <img src="13.jpg" alt="Toronto">
                <div class="spot-info">
                    <div class="country-rating">
                        <span class="country"> Kashmir</span>
                        <span class="rating">4.9 </span>
                    </div>
                    <div class="price">$150/person</div>
                </div>
                <a href="#" class="more-info">&rarr;</a>
            </div>
        </div>
        <button class="see-all">See All</button>
    </section>

    <section class="travel-spots">
        <h1>Best Travel Spots In World</h1>
        <div class="spots-container">
            <!-- Spot 1: Paris -->
            <div class="spot-card">
                <img src="15.jpg" alt="UAE">
                <div class="spot-info">
                    <div class="country-rating">
                        <span class="country"> Paris</span>
                        <span class="rating">5.0 </span>
                    </div>
                    <div class="price">$200/person</div>
                </div>
                <a href="#" class="more-info">&rarr;</a>
            </div>

            <!-- Spot 2: Singapore -->
            <div class="spot-card">
                <img src="16.jpg" alt="Singapore">
                <div class="spot-info">
                    <div class="country-rating">
                        <span class="country"> UAE</span>
                        <span class="rating">4.8 </span>
                    </div>
                    <div class="price">$300/person</div>
                </div>
                <a href="#" class="more-info">&rarr;</a>
            </div>

            <!-- Spot 3: New York -->
            <div class="spot-card">
                <img src="17.jpg" alt="New York">
                <div class="spot-info">
                    <div class="country-rating">
                        <span class="country"> Singapore</span>
                        <span class="rating">5.0 </span>
                    </div>
                    <div class="price">$100/person</div>
                </div>
                <a href="#" class="more-info">&rarr;</a>
            </div>

            <!-- Spot 4: Toronto -->
            <div class="spot-card">
                <img src="18.jpg" alt="Toronto">
                <div class="spot-info">
                    <div class="country-rating">
                        <span class="country"> New York</span>
                        <span class="rating">4.9 </span>
                    </div>
                    <div class="price">$150/person</div>
                </div>
                <a href="#" class="more-info">&rarr;</a>
            </div>
        </div>
        <button class="see-all">See All</button>
    </section>

 

   

<section id="offers" class="offers-section">
        <h1>Top Offers For You</h1>
        <p class="subtitle">
            Discover our exclusive selection of top offers tailored just for you. From unbeatable discounts to special promotions.
        </p>
        <div class="offers-container">
            <!-- Offer 1: Exclusive Discounts -->
            <div class="offer-card">
                <div class="offer-icon">
                    <img src="discount_879757.png" alt="Exclusive Discounts Icon">
                </div>
                <h2>Exclusive Discounts</h2>
                <p>Unlock exceptional savings with our exclusive discounts, designed to provide you with unbeatable value.</p>
            </div>

            <!-- Offer 2: Exceptional Value -->
            <div class="offer-card">
                <div class="offer-icon">
                    <img src="business_13353111.png" alt="Exceptional Value Icon">
                </div>
                <h2>Exceptional Value</h2>
                <p>Discover unparalleled value with our carefully selected offers that deliver more than just great savings.</p>
            </div>

            <!-- Offer 3: Tailored for You -->
            <div class="offer-card">
                <div class="offer-icon">
                    <img src="balance_913403.png" alt="Tailored for You Icon">
                </div>
                <h2>Tailored for You</h2>
                <p>Experience a collection of offers and recommendations meticulously tailored to your preferences.</p>
            </div>

            <!-- Offer 4: Handpicked Deals -->
            <div class="offer-card">
                <div class="offer-icon">
                    <img src="people_10046281.png" alt="Handpicked Deals Icon">
                </div>
                <h2>Handpicked Deals</h2>
                <p>Explore our handpicked deals, curated to offer you the very best in value and quality.</p>
            </div>
        </div>
    </section>


<!-- Booking Section -->
    <section id="booking" class="booking-form">
        <h2>Book Your Trip</h2>
        <form>
            <label for="destination">Destination</label>
            <input type="text" id="destination" name="destination" placeholder="Where do you want to go?" required>

            <label for="date">Travel Date</label>
            <input type="date" id="date" name="date" required>

            <label for="passengers">No. of Passengers</label>
            <input type="number" id="passengers" name="passengers" min="1" max="10" required>

            <label for="class">Class</label>
            <select id="class" name="class" required>
                <option value="economy">Economy</option>
                <option value="business">Business</option>
                <option value="first-class">First Class</option>
            </select>

            <button type="submit">Book Now</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer id="contact">
        <p>Contact Us: travelgo@example.com | Phone: +1 234 567 890</p>
        <p>&copy; 2024 TravelGo. All rights reserved.</p>
    </footer>

    <!-- JavaScript for Slideshow -->
    <script>
        let slideIndex = 0;
        showSlides();

        function showSlides() {
            let slides = document.getElementsByClassName("mySlides");
            let dots = document.getElementsByClassName("dot");
            for (let i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";  
            }
            slideIndex++;
            if (slideIndex > slides.length) {slideIndex = 1}    
            for (let i = 0; i < dots.length; i++) {
                dots[i].className = dots[i].className.replace(" active", "");
            }
            slides[slideIndex-1].style.display = "block";  
            dots[slideIndex-1].className += " active";
            setTimeout(showSlides, 3000); // Change image every 3 seconds
        }
    </script>
</body>
</html>
