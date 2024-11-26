<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Whitesquare</title>
    <link rel="stylesheet" href="styleуу.css">
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <div class="logo">whitesquare</div>
            <nav class="menu">
                <ul>
                    <li><a href="#" class="active">Home</a></li>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Partners</a></li>
                    <li><a href="#">Customers</a></li>
                    <li><a href="#">Projects</a></li>
                    <li><a href="#">Careers</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
            <div class="search">
                <input type="text" placeholder="Search">
                <button>Go</button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Fusce vitae nibh quis diam fermentum</h1>
        <p>Etiam adipiscing ultrices commodo.</p>
    </section>

    <!-- Tabs -->
    <section class="tabs">
        <div class="container">
            <div class="tab">Lorem Ipsum Dolop</div>
            <div class="tab">Ultricies Pellentesque</div>
            <div class="tab">Aliquam Ipsum</div>
            <div class="tab">Nullam Sed Mauris Ut</div>
        </div>
    </section>

    <!-- Content Section -->
    <section class="content">
        <div class="container">
            <div class="row">
                <div class="box about">
                    <h2>About Whitesquare</h2>
                    <p>In ultricies pellentesque massa a porta. Aliquam ipsum enim, hendrerit ut porttitor nec, ullamcorper et nulla.</p>
                    <a href="#">Read more</a>
                </div>
                <div class="box ceo">
                    <h2>A Word from our CEO</h2>
                    <p>In ultricies pellentesque massa a porta. Aliquam ipsum enim, hendrerit ut porttitor nec, ullamcorper et nulla.</p>
                    <p class="ceo-signature">Yane Naumoski, CEO</p>
                </div>
            </div>
            <div class="row">
                <div class="box services">
                    <h2>Services</h2>
                    <p>In ultricies pellentesque massa a porta. Aliquam ipsum enim, hendrerit ut porttitor nec, ullamcorper et nulla.</p>
                    <a href="#">Read more</a>
                </div>
                <div class="box teams">
                    <h2>Our Teams</h2>
                    <ul>
                        <li>Lorem Ipsum</li>
                        <li>Lorem Ipsum</li>
                        <li>Lorem Ipsum</li>
                    </ul>
                </div>
                <div class="box support">
                    <h2>24/7/365 Support</h2>
                    <p>In ultricies pellentesque massa a porta. Aliquam ipsum enim, hendrerit ut porttitor nec, ullamcorper et nulla.</p>
                    <a href="#">Read more</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-info">
                <p>&copy; 2012 Whitesquare. A pkiddo creation.</p>
            </div>
            <ul class="social">
                <li><a href="#">Facebook</a></li>
                <li><a href="#">Twitter</a></li>
                <li><a href="#">Google+</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
/* General Styles */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
}

/* Header */
.header {
  background: #fff;
  border-bottom: 1px solid #ccc;
  padding: 10px 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: #333;
}

.menu ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  gap: 15px;
}

.menu ul li {
  display: inline-block;
}

.menu ul li a {
  text-decoration: none;
  color: #555;
  padding: 5px 10px;
  transition: background 0.3s, color 0.3s;
}

.menu ul li a.active,
.menu ul li a:hover {
  background: #007bff;
  color: #fff;
  border-radius: 3px;
}

.search input {
  border: 1px solid #ccc;
  padding: 5px;
  border-radius: 3px;
}

.search button {
  padding: 5px 10px;
  background: #007bff;
  color: #fff;
  border: none;
  border-radius: 3px;
  cursor: pointer;
}

/* Hero */
.hero {
  text-align: center;
  padding: 40px 20px;
  background: #eee;
  border-bottom: 1px solid #ccc;
}

.hero h1 {
  font-size: 36px;
  margin: 0 0 10px 0;
}

.hero p {
  color: #666;
  font-size: 16px;
}

/* Tabs */
.tabs {
  background: #f9f9f9;
  padding: 20px 0;
}

.tabs .tab {
  background: #fff;
  padding: 10px 15px;
  text-align: center;
  border: 1px solid #ddd;
  border-radius: 3px;
  display: inline-block;
  margin-right: 5px;
  transition: background 0.3s, box-shadow 0.3s;
}

.tabs .tab:hover {
  background: #007bff;
  color: #fff;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Content */
.content {
  padding: 40px 0;
}

.row {
  display: flex;
  gap: 20px;
}

.box {
  flex: 1;
  background: #fff;
  border: 1px solid #ddd;
  padding: 20px;
  border-radius: 3px;
}

.box h2 {
  font-size: 18px;
  margin: 0 0 10px 0;
}

.box a {
  color: #007bff;
  text-decoration: none;
}

/* Footer */
.footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}

.footer .social {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 10px;
}

.footer .social li a {
  color: #007bff;
  text-decoration: none;
}
