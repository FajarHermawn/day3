# day3
dumbways

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dumbwaysday3</title>
    <link rel="stylesheet" href="css/style.css">
  <style>
    * {
  padding: 0;
  margin: 0;
}
header {
  background-color: rgb(238, 235, 235);
  width: 1280px;
}
body {
  width: 1200px;
  background-color: #ccd2d9;
}

.nav-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  list-style: none;
}
.logo {
  padding: 1rem 2rem;
  display: flex;
  justify-content: center;
  list-style: none;
  align-items: center;
}
.logo nav ul {
  display: flex;
  gap: 30px;
  justify-items: center;
  align-items: center;
  padding-left: 4rem;
  list-style: none;
}

.logo img {
  width: 30px;
}

button {
  background-color: black;
  color: white;
  margin: 0 2rem;
  border-radius: 20px;
  padding: 5px 10px;
}

.name {
  margin: 3rem 19rem;
  justify-items: center;
}

.tag nav ul {
  list-style: none;
}

.form-grub {
  padding: 0.5rem;
  position: relative;
}
h1 {
  padding-bottom: 1rem;
}
input {
  box-shadow: 0 4px 0 0 rgba(43, 42, 42, 0.2);
  border: 100px white;
  /* text-align: left;       Teks & cursor dimulai dari kiri */
  width: 310px;
  height: 30px;
}
.name button {
  margin: 1rem;
  padding: 5px 25px;
  text-align: center;
  margin-left: 15rem;
}

.form-select{
  left: 0;
  position: absolute;
  top: 100%;
}
  </style>
</head>
<body>
    <header>
    <div class="nav-bar">
        <div class="logo">
            <img src="image/Logo.png" alt="">
            <div>
                <nav>
                    <ul>
                        <li><strong>Home</strong></li>
                        <li>My project</li>
                    </ul>
                </nav>
            </div>
        </div>
        <div class="btn">
            <button>contact me</button>
        </div>
    </div>
</header>
<section>
    <div class="name">
        <h1>GET IN TOUCH</h1>
            <div class="form-grub">
                <div>
                <label for="Name">Name</label>
                </div>
                <input type="text" name="name" placeholder="your name" required>
            </div>
            <div class="form-grub">
                <div>
                <label for="Name">Email</label>
                </div>
                <input type="text" name="name" placeholder="Email" required>
            </div>
            <div class="form-grub">
                <div>
                <label for="Name">Phone number</label>
            </div>
                <input type="text" name="name" placeholder="Phone number" required>
            </div>
            <div class="form-grub">
                <div>
                <label for="Name">Subject</label>
            </div >
            <input type="text" name="name" placeholder="Select Subject" required>
            </div>
            <div class="form-grub">
                <div>
                <label for="Name">message</label>
            </div>
                <input type="text" name="name" placeholder="what do you want to say?" required>
            </div>
            <div>
                <button>submit</button>
            </div>
        </div>
    </div>
 
    
</section>
</body>
</html>
