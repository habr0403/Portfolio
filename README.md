<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="style.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Brandon Halloran</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <section id="home" class="hero bg-primary text-white py-5 mt-5">
        <div class="container text-center py-5">
            <h1 class="display-4">Behavioral Tech Supervisor/LADC</h1>
            <p class="lead">I disaprove what you say, but will defend to death your right to say it - Voltaire</p>
            <button class="btn btn-light btn-lg" data-bs-toggle="modal" data-bs-target="#contactModal">
                About Me
            </button>
        </div>
    </section>
    <section id="about" class="py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <h2>About Me</h2>
                    <p>I’m currently pursuing my LADC (Licensed Alcohol and Drug Counselor) certification, as I’m passionate about helping others and making a positive impact in the field of behavioral health. In the meantime, I work as a Behavioral Tech Supervisor at Northstar Behavioral Health, where I have the opportunity to lead a dedicated team and support individuals on their journey to recovery.
Outside of my professional life, I enjoy spending time on the softball field and playing with my dog. Whether it’s hitting a ball or just having fun with my furry companion, I find joy in staying active and balanced.
I’m driven by my commitment to both my career and personal well-being, and I’m excited to continue growing in my field while maintaining a fulfilling, healthy lifestyle.</p>
                </div>
                <div class="col-lg-6">
                    <img src="https://a-z-animals.com/media/2021/03/Westiepoo2.jpg" alt="Profile" class="img-fluid rounded">
                </div>
            </div>
        </div>
    </section>
    <section id="projects" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-5">Featured Projects</h2>
            <div class="row g-4">
                <div class="col-md-6 col-lg-4">
                    <div class="card h-100">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Forrest_Gump_running_route.png/800px-Forrest_Gump_running_route.png" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">Where Should Forrest RUn?</h5>
                            <p class="card-text">Here is a map of Forrest has RUn</p>
                            <li class="nav-item"><a class="nav-link" href="#home">Project</a></li>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4">
                    <div class="card h-100">
                        <img src="https://upload.wikimedia.org/wikipedia/en/thumb/1/16/Super_Bowl_logo.svg/220px-Super_Bowl_logo.svg.png" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">SuperBowl</h5>
                            <p class="card-text">Who will win the Superbowl?</p>
                           <li class="nav-item"><a class="nav-link" href="#home">Project</a></li>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <div class="modal fade" id="contactModal">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <section id="Contact" class="bg-light py-5">
                    <h5 class="modal-title">Contact Me</h5>
                    <button class="btn-close" data-bs-dismiss="modal"></button>
                </div>
                <div class="modal-body">
                    <form>
                        <div class="mb-3">
                            <label class="form-label">Brandon Halloran</label>
                            <input type="text" class="form-control">
                        </div>
                        <div class="mb-3">
                            <label class="form-label">brandonhalloran@yahoo.com</label>
                            <input type="email" class="form-control">
                        </div>
                        <div class="mb-3">
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2025 habr0403. All rights reserved.</p>
            <div class="social-links">
                <a href="#" class="text-white mx-2">GitHub</a>
                <a href="#" class="text-white mx-2">LinkedIn</a>
            </div>
        </div>
    </footer>
</body>
</html>
