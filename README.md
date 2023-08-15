# Landing-page
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content=
		"width=device-width, initial-scale=2.0">
	<link rel="stylesheet" href="landing.css">
	<title>Landing Page</title>
</head>

<body>
	<nav>
		<span class="sideMenuButton"
			onclick="openNavbar()">
		</span>

		<div class="navbar">
			<ul>
				<li><a href="#Home">Home</a></li>
                <li><a href="#">Portfolio</a></li>
				<li><a href="#">About Us</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</div>
	</nav>
	<div class="sideNavigationBar"
		id="sideNavigationBar">
		<a href="#" class="closeButton"
			onclick="closeNavbar()">
			
		</a>
		<a href="#">Home</a>
        <a href="#">Portfolio</a>
		<a href="#">About Us</a>
		<a href="#">Contact</a>
	</div>

	<div class="line" id="Home">
		<div class="side1">
			<h1>PhotoFilm</h1>
            <h3>Let us capture your moments!!</h3>
		</div>
		<div class="side2">
			<img src="https://media.istockphoto.com/id/834741464/photo/leisure-photos.jpg?s=612x612&w=0&k=20&c=PkXsoJ_r-r2L4Ltm7vE25V2ZTGNuvj1FvBAJN3JfkaA=" alt="camera"
				width="400">
		</div>
        <div class="side3">
            <img src="https://media.istockphoto.com/id/855413438/photo/take-every-chance-you-get-in-life.jpg?s=612x612&w=0&k=20&c=b6-PaRmnFXn8-pyLa-2ET223RkMJlUeAnAIwROzsLGY=" alt="camera"
            width="350">
        </div>
	</div>
    

    <section class="about" id="Services">
        <div class="content">
			<div class="title">
    </section>
    </div>

	<section class="about" id="Services">
		<div class="content">
			<div class="title">
				<h1>Our Services</h1>
			</div>
			<div class="boxes">
				<div class="box">
					<div class="topic">
						<a href="" target="_blank">
							Wedding Photography
						</a>
					</div>
					<p>
						Capture every moment of your special day with our professional wedding photography services.
					</p>
				</div>
				<div class="box">

					<div class="topic">
						<a href="" target="_blank">
							Product Photography
						</a>
					</div>
					<p>
						Highlight the best features of your products with our expertly crafted product photography.
					</p>
				</div>

				<div class="box">
					<div class="topic">
						<a href="" target="_blank">
							Potrait Photography
						</a>
					</div>
					<p>
						Bring out your unique personality and style with our personalized potrait photography sessions.
					</p>
				</div>
                <div class="box">
					<div class="topic">
						<a href="" target="_blank">
							Fashion Photography
						</a>
					</div>
					<p>
						Medium through which designers, brands, and creatives communicate their narratives.
					</p>
				</div>
                <div class="box">
					<div class="topic">
						<a href="" target="_blank">
							Aerial Photography
						</a>
					</div>
					<p>
						Capture bird's-eye view of your moments with our aerial photography services.
					</p>
				</div>
                <div class="box">
					<div class="topic">
						<a href="" target="_blank">
							Abstract Photography
						</a>
					</div>
					<p>
						Unveil the unseen and dare to tread a different path with our abstract photography services.
					</p>
				</div>
			</div>
		</div>
	</section>

	<section class="contact" id="contact">
		<div class="content">
			<section id="contact">
                <div class="contact-content">
                    <h2>Contact Us</h2>
                    <p>Want us to serve you? Let's get in touch!</p>
                    <form>
                        <input type="text" placeholder="Name">
                        <input type="email" placeholder="Email address">
                        <input type="text" placeholder="Service you want from us">
                        <button type="submit">Submit</button>
                    </form>
                </div>
            </section>
							
							
						</div>
						<div class="content1">
                            <span>
                                <h2><b>Our Address:</b></h2>
                            </span>
							<p>K-14, Ashok Marg, Panch Batti, C Scheme,</p>
                            <p>Ashok Nagar, Jaipur, Rajasthan 302001, India</p>
						</div>

					</div>
				</div>
			</div>
		</div>
	</section>
	
	<footer>
		<div class="footer">
			<span>
				Website by
				<a href="about.html"
					target="_blank">
					Bhumika
				</a>
			</span>
		</div>
	</footer>
	<script src="landing.js"></script>
</body>

</html>
