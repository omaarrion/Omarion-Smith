
 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <link rel="stylesheet" href="styles.css">
</head>
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.14.0/css/all.css" integrity="sha384-HzLeBuhoNPvSl5KYnjx0BT+WB0QEEqLprO+NBkkk5gbc67FTaL7XIGa2w1L0Xbgc" crossorigin="anonymous">
<body>
    <!-- Navbar --> 
        <nav class="navbar fixed-top navbar-dark bg-dark">
            <a href="#" class="navbar-brand">
                <img height="30" src="http://static1.squarespace.com/static/55c4ffcfe4b0b6679a5a2ff5/t/55c927aee4b0389a4f23a090/1594054577323/?format=1500w" alt="">
            </a>

            <!-- Mobile-->
            <button class="navbar-toggler"> data-toggler="collapse"
            data-target="mobileNavbar
            <ul class="nav d-none"> 
                <li class="nav-item">
                    <a href="#emojis" class="nav-link active">Emoji</a>
                </li>
                <li class="nav-item">
                    <a href="#alerts" class="nav-link active">Alerts</a>
                </li>
                <li class="nav-item">
                    <a href="#carousel" class="nav-link active">Carousel</a>
                </li>
                <li class="nav-item">
                    <a href="#forms" class="nav-link active">Form</a>
                </li>
                <li class="nav-item">
                    <a href="#modal" class="nav-link active">Modal</a>
                </li>
                <li class="nav-item">
                    <a href="#collapse" class="nav-link active">Collapse</a>
                </li>
                <li class="nav-item">
                    <a href="#dropdown" class="nav-link active">Dropdown</a>
                </li>
            </ul>
        </nav>

        <!-- Jumbotron -->
        <div class="jumbotron jumbotron-fluid py-5">
            <div class="container-fluid">
                <h1 class="display-4">Bootstrap</h1>
                <p>Bootstrap is a CSS Framework. It makes working with CSS easier, 
                especially when it comes to Responsive Design</p>
                <hr>
                <button href="https://getbootstrap.com/docs/4.5/getting-started/introduction/" class="btn btn-danger">Documentation</button>
            </div>
        </div>

    <!-- Container -->
    <div class="container-fluid">

        <!-- Emojis -->
        <div id="emojis" class="row">
            <h2 class="section-header">Emojis</h2>
        </div>
        <div class="row">
            <div id="column-1" class="col-2 text-center">
                <img class="icon" width="40"  src="https://cdn.shopify.com/s/files/1/1061/1924/files/Tongue_Out_Emoji_3_70x70.png?13752525173949329807" alt="emoji">
            </div>
            <div id="column-2" class="col-8 text-center">
                <img class="icon" width="40"  src="https://cdn.shopify.com/s/files/1/1061/1924/products/Slightly_Smiling_Emoji_Icon_34f238ed-d557-4161-b966-779d8f37b1ac_70x70.png?v=1485577096" alt="emoji">
            </div>
            <div id="column-3" class="col-2 text-center">
                <img class="icon" width="40" src="https://cdn.shopify.com/s/files/1/1061/1924/files/9_70x70.png?10625385272054259166" alt="emoji">
            </div>      
        </div>

        <!-- Alerts -->
        <div id="alerts" class="row">
            <h2 class="section-header">Alerts</h2>
        </div>
        <div class="alert alert-primary alert-dismissible fade show" role="alert">
            <strong>.alert-primary</strong>
            <button type="button" class="close" data-dismiss="alert" aria-label="Close">
                <span aria-hidden="true">&times;</span>
            </button>
        </div>

        <!-- Carousel -->

        <!-- Forms -->

        <!-- Modal -->

        <!-- Collapse -->

        <!-- Dropdown -->
    </div>

    <!-- <div class="container-sm">100% wide until small breakpoint ≥ 576px</div>
    <div class="container-md">100% wide until medium breakpoint ≥ 768px</div>
    <div class="container-lg">100% wide until large breakpoint ≥ 992px</div>
    <div class="container-xl">100% wide until extra large breakpoint ≥ 1200px</div> -->
    
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
</body>
</html>
