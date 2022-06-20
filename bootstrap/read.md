<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Base Bootstrap 4</title>

    <!-- lien bootstrap en local -->
    <link rel="stylesheet" href="bootstrap-local/scss/bootstrap.scss">

    <!-- lien CDNJS Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <!-- lien cdn Bootswatch -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootswatch@4.5.2/dist/cerulean/bootstrap.min.css" integrity="sha384-3fdgwJw17Bi87e1QQ4fsLn4rUFqWw//KU0g8TvV6quvahISRewev6/EocKNuJmEw" crossorigin="anonymous">

    <!-- lien css toujours en dernier -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- *****************************Navbar***************************** -->
    <nav class="navbar navbar-expand-lg navbar-light bg-dark d-flex justify-content-between sticky-top">
        <a class="navbar-brand text-warning d-flex href="index.html">
            <img src="img/logo.png" alt="" width="50" height="50" class="d-inline-block align-top">
            <h1 class="ml-4">Company Name</h1>
        </a>

        <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a href="" class="nav-link text-warning active border-bottom border-warning ">Home <span class="sr-only">(current)</span></a>
                    <!-- According to the Bootstrap documentation, the sr-only class is used to hide information that is intended only for screen readers from the layout of a renderd page. -->
                </li>
                <li class="nav-item">
                    <a href="#projects" class="nav-link text-warning">
                        Projects
                    </a>
                </li>
                <li class="nav-item">
                    <a href="#company" class="nav-link text-warning">
                        Company
                    </a>
                </li>
                <li class="nav-item">
                    <a href="#contact" class="nav-link text-warning">
                        Contact
                    </a>
                </li>
            </ul>
        </div>

        <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-warning my-2 my-sm-0" type="submit">Search</button>
        </form>
    </nav>
    
    <!-- *************************************JUMBOTRON********************************************* -->
    <!-- Un composant léger et flexible qui peut éventullement étendre l'intégralité de la fenêtre d'affichage pour présenter des messages marketing clés sur votre site. -->

    <div class="jumbotron jumbotron-fluid mb-0 d-flex align-items-center">
        <div class="container text-center text-light font-weight-bold">
            <q class="display-4 d-block">
                Quality needs precision and time... 
            </q>
            <!-- L'élément HTML <q> indique que le texte gu'il contient est une citation en incise. -->
            <q class="lead">
                It is our motto here at Company Name, to put our knowledge at your disposal to fulfill your vision.
            </q>
            <cite class="d-block text-right text-warning">Company Name</cite>
        </div>
    </div>

    <div class="container-fluid d-flex align-items-center justify-content-center">
        <i class="fas fa-chevron-down"></i>
    </div>


    <!-- ******************************************* PROJECTS PART ********************************************** -->

    <section class="row justify-content-around" id="projects">
        <h2 class="container-fluid text-center bg-dark text-warning mx-0 my-5 p-5">Our Projects</h2>

        <!-- *************************************3 images section projects************************************** -->
        <div class="card text-white col-3 p-1 bg-dark m-2">
            <img src="img/architecture-1.jpg" class="card-img" alt="...">

            <div class="card-img-overlay">
                <!-- Superpositions: card-img-overlay est utilisé pour définir l'image comme image d'arrière-plan de la carte et ajouter du texte sur l'image. -->
                <h5 class="card-title">Fake house</h5>

                <p class="card-text font-weight-bold shadow-lg p-3 mb-5 rounded">
                    This house is the one you need to live a great family life, you'll need a couple of money to
                    harmonized your stuffs. You should considere at this offer. Money don't do happiness, but it buy you
                    a house which gave you a part of joy you are searching for.
                </p>
                <p class="card-text">For sale since 1998</p>
            </div>
        </div>
        <div class="card text-white col-3 p-1 bg-dark m-2">
            <img src="img/architecture-2.jpg" class="card-img" alt="...">

            <div class="card-img-overlay">
                <!-- Superpositions: card-img-overlay est utilisé pour définir l'image comme image d'arrière-plan de la carte et ajouter du texte sur l'image. -->
                <h5 class="card-title">Fake house</h5>

                <p class="card-text font-weight-bold shadow-lg p-3 mb-5 rounded">
                    This house is the one you need to live a great family life, you'll need a couple of money to
                    harmonized your stuffs. You should considere at this offer. Money don't do happiness, but it buy you
                    a house which gave you a part of joy you are searching for.
                </p>
                <p class="card-text">For Rent for 3 months</p>
            </div>
        </div>
        <div class="card text-white col-3 p-1 bg-dark m-2">
            <img src="img/architecture-3.jpg" class="card-img" alt="...">

            <div class="card-img-overlay">
                <!-- Superpositions: card-img-overlay est utilisé pour définir l'image comme image d'arrière-plan de la carte et ajouter du texte sur l'image. -->
                <h5 class="card-title d-flex justify-content-between">Fake house <span class="bage badge-danger p-2">SOLD</span></h5>

                <p class="card-text font-weight-bold shadow-lg p-3 mb-5 rounded">
                    This house is the one you need to live a great family life, you'll need a couple of money to
                    harmonized your stuffs. You should considere at this offer. Money don't do happiness, but it buy you
                    a house which gave you a part of joy you are searching for.
                </p>
                <p class="card-text">Sold</p>
            </div>
        </div>

        <!-- **************************************** Link to Project's page ****************************************** -->
        <a href="" class="stretched-link col-12 text-right mr-5 pr-5 text-warning font-weight-bold">See more <i class="fas fa-long-arrow-alt-right"></i></a>
    </section>

    <!-- ******************************************* Company's part *********************************************** -->

    <section class="row justify-content-around" id="company">
        <h2 class="container-fluid text-center bg-dark text-warning mx-0 my-5 p-5">Our Company</h2>

        <!-- ***********************************6 card (team) section company ************************************* -->

        <div class="card[mb-3" style="max-width: 540px;">
            <div class="row no-gutters">

                <div class="col-md-4 my-auto">
                    <img src="img/worker-1-1.jpg" class="card-img" alt="...">
                </div>

                <div class="col-md-8">
                    <div class="card-body">
                        <h5>Fake employee</h5>

                        <p class="card-text">
                            This employee is not the best, not the worst but he work as much as we
                            can't fired him, we count on him and hope he never ask for a salary increase...
                        </p>

                        <p class="card-text"><small class="text-muted">Joined us in 2017</small></p>
                    </div>
                </div>

            </div>

        </div>

        <div class="card[mb-3" style="max-width: 540px;">
            <div class="row no-gutters">

                <div class="col-md-4 my-auto">
                    <img src="img/worker-2-2.jpg" class="card-img" alt="...">
                </div>

                <div class="col-md-8">
                    <div class="card-body">
                        <h5>Fake employee</h5>

                        <p class="card-text">
                            This employee is not the best, not the worst but he work as much as we
                            can't fired him, we count on him and hope he never ask for a salary increase...
                        </p>

                        <p class="card-text"><small class="text-muted">Joined us in 2017</small></p>
                    </div>
                </div>

            </div>

        </div>

        <div class="card[mb-3" style="max-width: 540px;">
            <div class="row no-gutters">

                <div class="col-md-4 my-auto">
                    <img src="img/worker-1-3.jpg" class="card-img" alt="...">
                </div>

                <div class="col-md-8">
                    <div class="card-body">
                        <h5>Fake employee</h5>

                        <p class="card-text">
                            This employee is not the best, not the worst but he work as much as we
                            can't fired him, we count on him and hope he never ask for a salary increase...
                        </p>

                        <p class="card-text"><small class="text-muted">Joined us in 2017</small></p>
                    </div>
                </div>

            </div>

        </div>

        <div class="card[mb-3" style="max-width: 540px;">
            <div class="row no-gutters">

                <div class="col-md-4 my-auto">
                    <img src="img/worker-1-5.jpg" class="card-img" alt="...">
                </div>

                <div class="col-md-8">
                    <div class="card-body">
                        <h5>Fake employee</h5>

                        <p class="card-text">
                            This employee is not the best, not the worst but he work as much as we
                            can't fired him, we count on him and hope he never ask for a salary increase...
                        </p>

                        <p class="card-text"><small class="text-muted">Joined us in 2017</small></p>
                    </div>
                </div>

            </div>

        </div>

        <div class="card[mb-3" style="max-width: 540px;">
            <div class="row no-gutters">

                <div class="col-md-4 my-auto">
                    <img src="img/worker-2-4.jpg" class="card-img" alt="...">
                </div>

                <div class="col-md-8">
                    <div class="card-body">
                        <h5>Fake employee</h5>

                        <p class="card-text">
                            This employee is not the best, not the worst but he work as much as we
                            can't fired him, we count on him and hope he never ask for a salary increase...
                        </p>

                        <p class="card-text"><small class="text-muted">Joined us in 2017</small></p>
                    </div>
                </div>

            </div>

        </div>

        <div class="card[mb-3" style="max-width: 540px;">
            <div class="row no-gutters">

                <div class="col-md-4 my-auto">
                    <img src="img/worker-2-6.jpg" class="card-img" alt="...">
                </div>

                <div class="col-md-8">
                    <div class="card-body">
                        <h5>Fake employee</h5>

                        <p class="card-text">
                            This employee is not the best, not the worst but he work as much as we
                            can't fired him, we count on him and hope he never ask for a salary increase...
                        </p>

                        <p class="card-text"><small class="text-muted">Joined us in 2017</small></p>
                    </div>
                </div>

            </div>

        </div>
    </section>
    
</body>
</html>
</html>