<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ICU Investigations</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f8f9f7;
  color: #1a1a1a;
}

header {
  background: linear-gradient(to right, #1b5e20, #2e7d32);
  color: white;
  padding: 15px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header h1 {
  margin: 0;
}

.hero {
  background-image: url('https://images.unsplash.com/photo-1508057198894-247b23fe5ade');
  background-size: cover;
  background-position: center;
  padding: 120px 20px;
  text-align: center;
  color: white;
}

.hero h2 {
  font-size: 40px;
  margin-bottom: 10px;
}

.btn {
  background: #2e7d32;
  color: white;
  padding: 12px 20px;
  margin: 10px;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}

.section {
  padding: 60px 20px;
  text-align: center;
}

.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.card {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

footer {
  background: linear-gradient(to right, #1b5e20, #2e7d32);
  color: white;
  padding: 40px 20px;
}

input, textarea {
  width: 90%;
  padding: 10px;
  margin: 10px;
  border-radius: 6px;
  border: 1px solid #ccc;
}
</style>

</head>

<body>

<header>
  <h1>ICU Investigations</h1>
  <div>
    <button class="btn">Free Consultation</button>
    <button class="btn">317-426-6002</button>
  </div>
</header>

<section class="hero">
  <h2>Answers You Need. Results You Can Trust.</h2>
  <p>Professional investigative services in Indianapolis</p>
</section>

<section class="section">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">Surveillance</div>
    <div class="card">Infidelity Investigations</div>
    <div class="card">Insurance Fraud</div>
    <div class="card">Background Checks</div>
    <div class="card">Missing Persons</div>
    <div class="card">Corporate Investigations</div>
  </div>
</section>

<section class="section">
  <h2>About Us</h2>
  <p>
    ICU Investigations LLC is a premier minority and woman-owned firm dedicated to providing comprehensive private investigation services. 
    Our expertise covers background checks, surveillance, relationship investigations, and more, all with a commitment to professionalism 
    and confidentiality, ensuring that each case is handled with integrity and tailored to meet the unique needs of our clients.
  </p>
</section>

<section class="section">
  <h2>Free Consultation</h2>
  <form action="mailto:icu@investigationsicu.com" method="POST" enctype="text/plain">
    <input type="text" placeholder="Your Name" required><br>
    <input type="email" placeholder="Your Email" required><br>
    <textarea placeholder="Tell us about your situation" required></textarea><br>
    <button class="btn">Send Message</button>
  </form>
</section>

<footer>
  <p>Licensed in Indiana | ICU Investigations LLC</p>
  <p>Follow Us: Instagram | LinkedIn</p>
</footer>

</body>
</html>
