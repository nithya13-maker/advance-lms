<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Learning Management System Portal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #28a745;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 0.5rem 0;
        }
        nav a {
            color: #fff;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the LMS</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="login.html">Login</a>
        <a href="signup.html">Sign Up</a>
        <a href="courses.html">Courses</a>
        <a href="about.html">About</a>
    </nav>

    <footer>
        &copy; 2024 Learning Management System. All Rights Reserved.
    </footer>
</body>
</html>

<!-- Home Page: index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - LMS</title>
    <style>
        .hero {
            text-align: center;
            background-color: #dff9fb;
            padding: 2rem 1rem;
            margin-bottom: 2rem;
        }
        .hero h1 {
            margin: 0;
        }
        .features {
            display: flex;
            justify-content: space-around;
            margin-bottom: 2rem;
        }
        .feature-card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 30%;
        }
    </style>
</head>
<body>
    <div class="hero">
        <h1>Learn Anytime, Anywhere</h1>
        <p>Your journey to knowledge starts here. Discover courses, connect with educators, and achieve your learning goals.</p>
    </div>

    <section class="features">
        <div class="feature-card">
            <h2>Wide Range of Courses</h2>
            <p>Access courses across multiple disciplines, tailored to your learning needs.</p>
        </div>
        <div class="feature-card">
            <h2>Expert Educators</h2>
            <p>Learn from industry experts and highly qualified instructors.</p>
        </div>
        <div class="feature-card">
            <h2>Flexible Learning</h2>
            <p>Study at your own pace with flexible and engaging course content.</p>
        </div>
    </section>
</body>
</html>

<!-- Login Page: login.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - LMS</title>
    <style>
        .login-form {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 1rem auto;
            padding: 1rem;
            max-width: 400px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .login-form h2 {
            margin-top: 0;
        }
        .form-group {
            margin-bottom: 1rem;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
        }
        .form-group input, .form-group button {
            width: 100%;
            padding: 0.5rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .form-group button {
            background-color: #28a745;
            color: #fff;
            font-weight: bold;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <section class="login-form">
        <h2>Login to Your Account</h2>
        <form>
            <div class="form-group">
                <label for="email">Email or Username</label>
                <input type="text" id="email" name="email" placeholder="Enter email or username">
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" placeholder="Enter password">
            </div>
            <div class="form-group">
                <button type="submit">Login</button>
            </div>
            <p><a href="#">Forgotten password?</a> | <a href="signup.html">Sign up</a></p>
        </form>
    </section>
</body>
</html>

<!-- Sign-Up Page: signup.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up - LMS</title>
    <style>
        .signup-form {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 1rem auto;
            padding: 1rem;
            max-width: 400px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .signup-form h2 {
            margin-top: 0;
        }
        .form-group {
            margin-bottom: 1rem;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
        }
        .form-group input, .form-group button {
            width: 100%;
            padding: 0.5rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .form-group button {
            background-color: #28a745;
            color: #fff;
            font-weight: bold;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <section class="signup-form">
        <h2>Create an Account</h2>
        <form>
            <div class="form-group">
                <label for="fullname">Full Name</label>
                <input type="text" id="fullname" name="fullname" placeholder="Enter your full name">
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="Enter your email">
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" placeholder="Create a password">
            </div>
            <div class="form-group">
                <label for="confirm-password">Confirm Password</label>
                <input type="password" id="confirm-password" name="confirm-password" placeholder="Confirm your password">
            </div>
            <div class="form-group">
                <button type="submit">Sign Up</button>
            </div>
        </form>
    </section>
</body>
</html>

<!-- Upload Course Page: courses.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Upload Course - LMS</title>
    <style>
        .upload-form {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 1rem auto;
            padding: 1rem;
            max-width: 400px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .upload-form h2 {
            margin-top: 0;
        }
        .form-group {
            margin-bottom: 1rem;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
        }
        .form-group input, .form-group textarea, .form-group button {
            width: 100%;
            padding: 0.5rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .form-group button {
            background-color: #28a745;
            color: #fff;
            font-weight: bold;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <section class="upload-form">
        <h2>Upload Course</h2>
        <form>
            <div class="form-group">
                <label for="course-name">Course Name</label>
                <input type="text" id="course-name" name="course-name" placeholder="Enter course name">
            </div>
            <div class="form-group">
                <label for="course-description">Course Description</label>
                <textarea id="course-description" name="course-description" placeholder="Enter course description"></textarea>
            </div>
            <div class="form-group">
                <label for="course-material">Course Material (PDF, DOC, etc.)</label>
                <input type="file" id="course-material" name="course-material">
            </div>
            <div class="form-group">
                <button type="submit">Upload Course</button>
            </div>
        </form>
    </section>
</body>
</html>
