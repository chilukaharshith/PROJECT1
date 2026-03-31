<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hospital Login</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
}

.login-container{
    background:rgba(255,255,255,0.1);
    backdrop-filter:blur(15px);
    padding:40px;
    width:350px;
    border-radius:15px;
    box-shadow:0 8px 32px rgba(0,0,0,0.4);
    text-align:center;
    color:white;
}

.login-container img{
    width:80px;
    margin-bottom:15px;
}

.login-container h2{
    margin-bottom:25px;
    font-weight:600;
}

.input-box{
    position:relative;
    margin:15px 0;
}

.input-box input{
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
    outline:none;
    font-size:15px;
}

.input-box input:focus{
    border:2px solid #1eff00;
}


.login-btn{
    width:100%;
    padding:12px;
    margin-top:15px;
    background:linear-gradient(to right,#00ff73,#00ff80);
    border:none;
    border-radius:8px;
    color:white;
    font-size:16px;
    font-weight:bold;
    cursor:pointer;
    transition:0.3s;
}

.login-btn:hover{
    transform:scale(1.05);
    background:linear-gradient(to right,#0072ff,#00c6ff);
}


.extra{
    margin-top:15px;
    font-size:14px;
}

.extra a{
    color:#00c6ff;
    text-decoration:none;
}

.extra a:hover{
    text-decoration:underline;
}


@media(max-width:400px){
    .login-container{
        width:90%;
    }
}

</style>
</head>

<body>

<div class="login-container">
    
    <img src="https://cdn-icons-png.flaticon.com/512/2966/2966480.png" alt="Hospital Logo">

    <h2>Hospital Management Login</h2>

    
        <div class="input-box">
            <input type="text" placeholder="Username or Email" required>
        </div>

        <div class="input-box">
            <input type="password" placeholder="Password" required>
        </div>
        <a href="home2.html">

        <button class="login-btn">Login</button>
        </a>
    

    <div class="extra">
        <p><a href="#">Forgot Password?</a></p>
        <p>New User? <a href="#">Register</a></p>
    </div>

</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">


<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

/* Body */
body{
    background:#f4f8fb;
}

/* Navbar */
nav{
    background:linear-gradient(to right,#0f2027,#203a43,#2c5364);
    padding:15px 50px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    color:white;
}

nav h2{
    font-weight:600;
}

nav ul{
    list-style:none;
    display:flex;
}

nav ul li{
    margin-left:20px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-weight:500;
}

nav ul li a:hover{
    color:#00c6ff;
}

/* Hero Section */
.hero{
    background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1586773860418-d37222d8fce3');
    background-size:cover;
    background-position:center;
    height:80vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
    padding:20px;
}

.hero h1{
    font-size:45px;
    margin-bottom:15px;
}

.hero p{
    font-size:18px;
    margin-bottom:20px;
}

.hero button{
    padding:12px 25px;
    background:#00c6ff;
    border:none;
    border-radius:5px;
    color:white;
    font-size:16px;
    cursor:pointer;
}

.hero button:hover{
    background:#0072ff;
}

/* Services Section */
.services{
    padding:60px 20px;
    text-align:center;
}

.services h2{
    margin-bottom:40px;
    color:#203a43;
}

.service-container{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
}

.service-card{
    background:white;
    width:280px;
    margin:15px;
    padding:25px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    transition:0.3s;
}

.service-card:hover{
    transform:translateY(-8px);
}

.service-card h3{
    margin-bottom:15px;
    color:#0072ff;
}

.service-card p{
    font-size:14px;
    color:#555;
}

/* Footer */
footer{
    background:#203a43;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}

@media(max-width:768px){
    nav{
        flex-direction:column;
    }
    nav ul{
        margin-top:10px;
    }
}
</style>
</head>

<body>

<!-- Navigation -->
<nav>
    <h2>CityCare Hospital</h2>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="login2.html">Login</a></li>
    </ul>
</nav>


<section class="hero">
    <div>
        <h1>Compassionate Care, Advanced Medicine</h1>
        <p>Providing world-class healthcare services with experienced doctors and modern facilities.</p>
        <a href="appointment2.html">
        <button>Book Appointment</button>
        </a>
    </div>
</section>


<section class="services">
    <h2>Our Medical Services</h2>

    <div class="service-container">

        <div class="service-card">
            <h3>Emergency Care</h3>
            <p>24/7 emergency medical services with fully equipped trauma center and experienced emergency physicians.</p>
        </div>

        <div class="service-card">
            <h3>Cardiology</h3>
            <p>Advanced heart care including ECG, angioplasty, bypass surgery, and cardiac rehabilitation programs.</p>
        </div>

        <div class="service-card">
            <h3>Neurology</h3>
            <p>Comprehensive treatment for brain and nervous system disorders using latest diagnostic technology.</p>
        </div>

        <div class="service-card">
            <h3>Pediatrics</h3>
            <p>Specialized healthcare services for infants, children, and adolescents with child-friendly environment.</p>
        </div>

        <div class="service-card">
            <h3>Orthopedics</h3>
            <p>Expert treatment for bone and joint problems including fractures, arthritis, and sports injuries.</p>
        </div>
        <div class="service-card">
            <h3>Diagnostic Services</h3>
            <p>Modern laboratory and imaging services including MRI, CT Scan, X-Ray, and blood tests.</p>
        </div>

    </div>
</section>

<footer>
    <p>© 2026 CityCare Hospital | 24/7 Healthcare Services | Hyderabad, India</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Book Appointment - CityCare Hospital</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body{
    background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}


.container{
    background:rgba(255,255,255,0.1);
    backdrop-filter:blur(15px);
    padding:35px;
    width:420px;
    border-radius:15px;
    box-shadow:0 8px 32px rgba(0,0,0,0.4);
    color:white;
}

.container h2{
    text-align:center;
    margin-bottom:20px;
}

.input-box{
   margin:12px 0;
}

.input-box label{
    font-size:14px;
}

.input-box input,
.input-box select{
    width:100%;
    padding:10px;
    margin-top:5px;
    border:none;
    border-radius:8px;
    outline:none;
}

/* Button */
button{
    width:100%;
    padding:12px;
    margin-top:15px;
    background:linear-gradient(to right,#00c6ff,#0072ff);
    border:none;
    border-radius:8px;
    color:white;
    font-size:16px;
    font-weight:bold;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    transform:scale(1.05);
    background:linear-gradient(to right,#0072ff,#00c6ff);
}

/* Success message */
.success{
    display:none;
    text-align:center;
    margin-top:20px;
    font-weight:bold;
    color:#00ffcc;
}

/* Show success after clicking submit */
#book:target{
    display:block;
}

@media(max-width:450px){
    .container{
        width:90%;
    }
}
</style>
</head>

<body>

<div class="container">

    <h2>Book Appointment</h2>

    <form action="#book">

        <div class="input-box">
            <label>Select Doctor</label>
            <select required>
                <option value="">-- Choose Doctor --</option>
                <option>Dr. Ramesh (Cardiologist) - ₹800</option>
                <option>Dr. Priya (Neurologist) - ₹900</option>
                <option>Dr. Arjun (Orthopedic) - ₹700</option>
                <option>Dr. Sneha (Pediatrician) - ₹600</option>
            </select>
        </div>

        <div class="input-box">
            <label>Patient Name</label>
            <input type="text" required>
        </div>

        <div class="input-box">
            <label>Age</label>
            <input type="number" required>
        </div>

        <div class="input-box">
            <label>Gender</label>
            <select required>
                <option value="">-- Select Gender --</option>
                <option>Male</option>
                <option>Female</option>
                <option>Other</option>
            </select>
        </div>

        <div class="input-box">
            <label>Select Date</label>
            <input type="date" required>
        </div>

        <div class="input-box">
            <label>Select Time</label>
            <input type="time" required>
        </div>

        <button type="submit">Book Appointment</button>

    </form>

    <!-- Success Message -->
    <div id="book" class="success">
        ✅ Appointment Booked Successfully!
    </div>

</div>

</body>
</html>
