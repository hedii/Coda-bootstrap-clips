# Coda-bootstrap-clips
Bootstrap Clips for Panic Coda 2

## Installation
Copy Bootstrap.clips in Coda Clips folder:

*/Users/[OSX Username]/Library/Application Support/Coda 2/Clips*

## Usage
#### Starter page
Type `bootstrap` and press **`TAB`**
```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
	<meta name="description" content="">
	<meta name="keywords" content="">
	<meta name="author" content="">

	<!-- css -->
	<link href="css/bootstrap.min.css" rel="stylesheet">
	<link href="css/style.css" rel="stylesheet">

	<!--[if lt IE 9]>
		<script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
		<script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
	<![endif]-->
</head>
<body>

	<header id="site-header">
	</header><!-- #site-header -->

	<main id="site-content" role="main">
		
	</main><!-- #site-content -->

	<footer id="site-footer" role="contentinfo">
	</footer><!-- #site-footer -->

	<!-- js -->
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
	<script src="js/bootstrap.min.js"></script>
	<script src="js/script.js"></script>

</body>
</html>
```

#### Navbar
Type `navbar` and press **`TAB`**
```html
<nav class="navbar navbar-default" role="navigation">
	<div class="container-fluid">
		<div class="navbar-header">
			<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
				<span class="sr-only">Toggle navigation</span>
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
			</button>
			<a class="navbar-brand" href="#"></a>
		</div>
		<div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
			<ul class="nav navbar-nav navbar-right">
				<li><a href="#">Link</a></li>
			</ul>
		</div><!-- .navbar-collapse -->
	</div><!-- .container-fluid -->
</nav><!-- .navbar -->
```

#### Container div
Type `container` and press **`TAB`**
```html
<div class="container">
	
</div><!-- .container -->
```

#### Container fluid div
Type `*container-fluid*` and press **`TAB`**
```html
<div class="container-fluid">
	
</div><!-- .container-fluid -->
```

#### Row div
Type *row* and press **`TAB`**
```html
<div class="row">
	
</div><!-- .row -->
```

#### Column xs
Type *col-xs* and press **`TAB`**
```html
<div class="col-xs-">
	
</div>
```

#### Column sm
Type *col-sm* and press **`TAB`**
```html
<div class="col-sm-">
	
</div>
```

#### Column md
Type *col-md* and press **`TAB`**
```html
<div class="col-md-">
	
</div>
```

#### Column lg
Type *col-lg* and press **`TAB`**
```html
<div class="col-lg-">
	
</div>
```

#### Form group
Type *form-group* and press **`TAB`**
```html
<div class="form-group">
	<label for=""></label>
	<input type="" class="form-control" id="" name="" placeholder="">
</div>
```

#### Pagination
Type *pagination* and press **`TAB`**
```html
<nav>
	<ul class="pagination">
		<li>
			<a href="#" aria-label="Previous">
				<span aria-hidden="true">&laquo;</span>
			</a>
		</li>
		<li><a href="#">1</a></li>
		<li><a href="#">2</a></li>
		<li><a href="#">3</a></li>
		<li><a href="#">4</a></li>
		<li><a href="#">5</a></li>
		<li>
			<a href="#" aria-label="Next">
				<span aria-hidden="true">&raquo;</span>
			</a>
		</li>
	</ul>
</nav>
```

#### Alert success
Type *alert-success* and press **`TAB`**
```html
<div class="success alert-success" role="alert"></div>
```

#### Alert info
Type *alert-info* and press **`TAB`**
```html
<div class="alert alert-info" role="alert"></div>
```

#### Alert warning
Type *alert-warning* and press **`TAB`**
```html
<div class="alert alert-warning" role="alert"></div>
```

#### Alert danger
Type *alert-danger* and press **`TAB`**
```html
<div class="alert alert-danger" role="alert"></div>
```

