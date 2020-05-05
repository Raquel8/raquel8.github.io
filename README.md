<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Future Portfolio Page</title>
    <link rel="stylesheet" href="homePage.css" type="text/css" />
    <link rel="stylesheet" href="defaultStyle.css" type="text/css" />
    <!-- bootstrap stylesheet -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
        integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">
    <!-- FontAwesome -->
    <script src="https://kit.fontawesome.com/938a18ead6.js" crossorigin="anonymous"></script>

</head>

<body id="topPage" data-spy="scroll" data-offset="0" data-target="topPage">
    <!-- BS navbar -->
    <nav class="navbar navbar-expand-lg customNavBg">
        <a class="navbar-brand" href="index.html"><b>VCD 5D</b></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#mycustomNav"
            aria-controls="navbarsExample09" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon">
                <i class="fas fa-bars"></i>
            </span>
            </span>
        </button>

        <div class="collapse navbar-collapse" id="mycustomNav">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="index.html">Home</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link" href="cssTraining.html">Css Traning</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="floatPositionActivity.html">Float Activity</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="bsGridPractice.html">BS Grid Practice</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown" aria-haspopup="true"
                        aria-expanded="false">Contact</a>
                    <div class="dropdown-menu">
                        <a class="dropdown-item" href="mailto:lariosr29@hotmail.com">Email</a>
                        <a class="dropdown-item" href="https://github.com/raquel8" target="_blank">Github page</a>
                        <a class="dropdown-item" href="https://raquel8.github.io/" target="_blank">VCD 5d website</a>
                    </div>
                </li>
            </ul>
            <form class="form-inline my-2 my-md-0">
                <input class="form-control" type="text" placeholder="Search" aria-label="Search">
            </form>
        </div>
    </nav>

    <!-- content container -->
    <div class="container-fluid">

        <!-- bio title -->
        <section class="sectionTitle">
            <h2>About Me</h2>
            <hr />
        </section>

        <!-- description section -->
        <div class="row align-items-center customDescriptionSection">
            <div class="col-12 col-md-4 avataCol justify-content-center">
                <a href="contact.html">
                    <img class="circleImage" src="/assets/images/drawing.jpg" height="auto" width="90">
                </a>
            </div>
            <div class="col-12 col-md-4 biotTxt">
                <p> Hi my name is Raquel Larios. I'm a Visual Communication Major.</p>
            </div>
            <div class="col-12 col-md-4 avataCol justify-content-center">
                <a href="contact.html">
                    <img class="circleImage" src="/assets/images/drawing.jpg" height="auto" width="90">
                </a>
            </div>
        </div>

        <!-- project title -->
        <section class="sectionTitle">
            <h2>Projects Gallery</h2>
            <hr />
        </section>

        <!-- projects card section  -->
        <!-- Doggo project -->
        <div class="row justify-content-center projectGallerySection">
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="card">
                    <img src="/assets/images/dog.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="cagrd-title">Dogg Project</h5>
                        <p class="card-text">Some quick example 
                            card's content.</p>
                        <a href="#" class="btn projectCardBtn" data-toggle="modal" data-target="#cupcakeeModal">View
                            Project</a>
                    </div>
                </div>
            </div>

            <!-- Cupcake Project Modal -->
            <div class="modal fade customProjectModal" id="cupcakeModal" tabindex="-1" role="dialog"
                aria-labelledby="myLargeModalLabel" aria-hidden="true">
                <div class="modal-dialog modal-lg modal-dialog-centered">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                <span aria-hidden="true">&times;</span>
                            </button>
                        </div>
                        <div class="modal-body">
                            <!-- Cupcake Carousels -->
                            <div id="Carousel" class="carousel slide customProjectCarousel" data-ride="carousel">
                                <ol class="carousel-indicators">
                                    <li data-target="#cupcakeCarousel" data-slide-to="0" class="active"></li>
                                    <li data-target="#cupcakeCarousel" data-slide-to="1"></li>
                                    <li data-target="#cupcakeCarousel" data-slide-to="2"></li>
                                </ol>
                                <div class="carousel-inner">
                                    <div class="carousel-item active">
                                        <img class="d-block w-100" src="/assets/images/doog.JPG" alt="First slide">
                                    </div>
                                    <div class="carousel-item">
                                        <img class="d-block w-100" src="/assets/images/doggo.jpg" alt="Second slide">
                                    </div>
                                    <div class="carousel-item">
                                        <img class="d-block w-100" src="/assets/images/doog.JPG" alt="Third slide">
                                        <div class="carousel-caption d-none d-md-block">
                                            <h5>...</h5>
                                            <p>...</p>
                                        </div>
                                    </div>
                                </div>
                                <a class="carousel-control-prev" href="#cupcakeCarousel" role="button"
                                    data-slide="prev">
                                    <span class="" aria-hidden="true">
                                        <i class="fas fa-chevron-left"></i>
                                    </span>
                                    <span class="sr-only">Previous</span>
                                </a>
                                <a class="carousel-control-next" href="#cupcakeCarousel" role="button"
                                    data-slide="next">
                                    <span class="" aria-hidden="true">
                                        <i class="fas fa-chevron-right"></i>
                                    </span>
                                    <span class="sr-only">Next</span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Fruit Project -->
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="card">
                    <img src="/assets/images/fire.JPG" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Camp Fire</h5>
                        <p class="card-text">Some quick example 
                        <a href="#" class="btn projectCardBtn" data-toggle="modal" data-target="#fruitModal">View
                            Project</a>
                    </div>
                </div>
            </div>

            <!-- fruit project modal -->
            <div class="modal fade customProjectModal" id="fruitModal" tabindex="-1" role="dialog"
                aria-labelledby="exampleModalScrollableTitle" aria-hidden="true">
                <div class="modal-dialog modal-dialog-scrollable modal-lg" role="document">
                    <div class="modal-content">
                        <div class="modal-header">
                            <h5 class="modal-title" id="exampleModalScrollableTitle">Fruit Project</h5>
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                <span aria-hidden="true">&times;</span>
                            </button>
                        </div>
                        <div class="modal-body">
                            <p>Camping trip</p>
                            <!-- fruit casousel images -->
                            <div id="fruitCarousel" class="carousel slide customProjectCarousel" data-ride="carousel">
                                <ol class="carousel-indicators">
                                    <li data-target="#fruitCarousel" data-slide-to="0" class="active"></li>
                                    <li data-target="#fruitCarousel" data-slide-to="1"></li>
                                    <li data-target="#fruitCarousel" data-slide-to="2"></li>
                                </ol>
                                <div class="carousel-inner">
                                    <!-- first image -->
                                    <div class="carousel-item active">
                                        <img src="/assets/images/marshmellow.jpg" class="d-block w-100" alt="...">
                                        <div class="carousel-caption d-none d-md-block">
                                            <h5>Kiwi image</h5>
                                            <p> kiwi kiwi kiwi</p>
                                        </div>
                                    </div>
                                    <!-- second image -->
                                    <div class="carousel-item">
                                        <img src="/assets/images/fire.JPG" class="d-block w-100" alt="...">
                                        <div class="carousel-caption d-none d-md-block">
                                            <h5>strawberry</h5>
                                            <p>strawberry strawberry strawberry</p>
                                        </div>
                                    </div>
                                    <!-- third image -->
                                    <div class="carousel-item">
                                        <img src="/assets/images/nature.JPG" class="d-block w-100" alt="...">
                                        <div class="carousel-caption d-none d-md-block">
                                            <h5>apple</h5>
                                            <p>apple apple apple</p>
                                        </div>
                                    </div>
                                </div>
                                <a class="carousel-control-prev" href="#fruitCarousel" role="button" data-slide="prev">
                                    <span class="" aria-hidden="true">
                                        <i class="fas fa-chevron-left"></i>
                                    </span>
                                    <span class="sr-only">Previous</span>
                                </a>
                                <a class="carousel-control-next" href="#fruitCarousel" role="button" data-slide="next">
                                    <span class="" aria-hidden="true">
                                        <i class="fas fa-chevron-right"></i>
                                    </span>
                                    <span class="sr-only">Next</span>
                                </a>
                            </div>

                        </div>
                    </div>
                </div>
            </div>

            <!-- furniture project -->
            <div class="col-sm-6 col-md-4 col-lg-3">
                <div class="card">
                    <img src="/assets/images/drawing.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Furniture Project</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the
                            card's content.</p>
                        <a href="#" class="btn projectCardBtn">View Project</a>
                    </div>
                </div>
            </div>

            

        <!-- pseudo classes warm up activity -->
        <!-- <a class="tesla-link" target="_blank" href="https://www.tesla.com/">Tesla website</a> -->

        <!-- Tool tip and scroll spy -->
        <div class="row customToolTip">
            <div class="col-12">
                <a class="btn toTop" data-toggle="tooltip" data-placement="right" title="Scroll to Top" href="#topPage">
                    <span>
                        <i class="fas fa-chevron-circle-up"></i>
                    </span>
                </a>
            </div>
        </div>
    </div>

    <!-- fixed footer -->
    <a href="index.html">
        <footer>
            <p>This is sticky footer</p>
        </footer>
    </a>

    <!-- boostrap script -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
        integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous">
    </script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
        integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous">
    </script>

    <!-- custom script for tool tip and smooth scroll -->
    <script>
        $(document).ready(function () {
            // tool tip
            $('[data-toggle="tooltip"]').tooltip();

            // smooth scroll for scroll spy
            $("a.toTop").on('click', function (event) {
                if (this.hash !== "") {
                    event.preventDefault();
                    var hash = this.hash;

                    $('html, body').animate({
                        scrollTop: $(hash).offset().top
                    }, 800, function () {
                        window.location.hash = hash;
                    });
                }
            });
        });
    </script>

</body>

</html>