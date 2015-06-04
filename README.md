# Coda-bootstrap-clips
Twitter Bootstrap 3.x Clips for Panic Coda 2

## Note
- All resulting html code from these clips is indented with standard tabs.
Bootstrap two spaces sucks.
- Some clips like `table + TAB`, `select + TAB` or `form + TAB` are not included to avoid conflicts because they are already here in coda default clips.

New clips will come soon...

## Installation
Copy [Bootstrap.clips](https://github.com/hedii/Coda-bootstrap-clips/blob/master/Bootstrap.clips) and paste it in the Coda Clips folder:

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

### Grid system

#### Container div
Type `container` and press **`TAB`**
```html
<div class="container">
	
</div><!-- .container -->
```

#### Container fluid div
Type `container-fluid` and press **`TAB`**
```html
<div class="container-fluid">
	
</div><!-- .container-fluid -->
```

#### Row div
Type `row` and press **`TAB`**
```html
<div class="row">
	
</div><!-- .row -->
```

#### Column xs
Type `col-xs` and press **`TAB`**
```html
<div class="col-xs-">
	
</div>
```

#### Column sm
Type `col-sm` and press **`TAB`**
```html
<div class="col-sm-">
	
</div>
```

#### Column md
Type `col-md` and press **`TAB`**
```html
<div class="col-md-">
	
</div>
```

#### Column lg
Type `col-lg` and press **`TAB`**
```html
<div class="col-lg-">
	
</div>
```

### Typography

#### Lead
Type `lead` and press **`TAB`**
```html
<p class="lead">
	
</p>
```

#### Blockquote
Type `blockquote` and press **`TAB`**
```html
<blockquote>
	<p></p>
</blockquote>
```

### Tables

#### Table striped
Type `table-striped` and press **`TAB`**
```html
<table class="table table-striped">
	
</table>
```

#### Table bordered
Type `table-bordered` and press **`TAB`**
```html
<table class="table table-bordered">
	
</table>
```

#### Table hover
Type `table-hover` and press **`TAB`**
```html
<table class="table table-hover">
	
</table>
```

#### Table condensed
Type `table-condensed` and press **`TAB`**
```html
<table class="table table-condensed">
	
</table>
```

#### Table responsive
Type `table-responsive` and press **`TAB`**
```html
<div class="table-responsive">
	<table class="table">
		
	</table>
</div>
```

### Forms

#### Inline form
Type `inline-form` and press **`TAB`**
```html
<form class="form-inline">
	
</form>
```

#### Horizontal form
Type `horizontal-form` and press **`TAB`**
```html
<form class="form-horizontal">
	
</form>
```

#### Form group
Type `form-group` and press **`TAB`**
```html
<div class="form-group">
	<label for=""></label>
	<input type="" class="form-control" id="" name="" placeholder="">
</div>
```

#### Checkbox
Type `checkbox` and press **`TAB`**
```html
<div class="checkbox">
	<label>
		<input type="checkbox" name="" id="" value="">
		
	</label>
</div>
```

#### Radio
Type `radio` and press **`TAB`**
```html
<div class="radio">
	<label>
		<input type="radio" name="" id="" value="">
		
	</label>
</div>
```

#### Inline checkbox
Type `checkbox-inline` and press **`TAB`**
```html
<label class="checkbox-inline">
	<input type="checkbox" name="" id="" value=""> 
</label>
```

#### Inline radio
Type `radio-inline` and press **`TAB`**
```html
<label class="radio-inline">
	<input type="radio" name="" id="" value=""> 
</label>
```

#### Multiple select
Type `select-multiple` and press **`TAB`**
```html
<select multiple class="form-control" name="">
	<option value=""></option>
	<option value=""></option>
</select>
```

### Buttons

#### Default button
Type `btn-default` and press **`TAB`**
```html
<a href="" class="btn btn-default"></a>
```

#### Primary button
Type `btn-primary` and press **`TAB`**
```html
<a href="" class="btn btn-primary"></a>
```

#### Success button
Type `btn-success` and press **`TAB`**
```html
<a href="" class="btn btn-success"></a>
```

#### Info button
Type `btn-info` and press **`TAB`**
```html
<a href="" class="btn btn-info"></a>
```

#### Warning button
Type `btn-warning` and press **`TAB`**
```html
<a href="" class="btn btn-warning"></a>
```

#### Danger button
Type `btn-danger` and press **`TAB`**
```html
<a href="" class="btn btn-danger"></a>
```

#### Link button
Type `btn-link` and press **`TAB`**
```html
<a href="" class="btn btn-link"></a>
```

### Images

#### Responsive image
Type `img-responsive` and press **`TAB`**
```html
<img class="img-responsive" src="" alt="">
```

#### Rounded image
Type `img-rounded` and press **`TAB`**
```html
<img class="img-rounded" src="" alt="">
```

#### Circle image
Type `img-circle` and press **`TAB`**
```html
<img class="img-circle" src="" alt="">
```

#### Thumbnail image
Type `img-thumbnail` and press **`TAB`**
```html
<img class="img-thumbnail" src="" alt="">
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

----------------------------------------------

### Components

#### Pagination
Type `pagination` and press **`TAB`**
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
Type `alert-success` and press **`TAB`**
```html
<div class="success alert-success" role="alert"></div>
```

#### Alert info
Type `alert-info` and press **`TAB`**
```html
<div class="alert alert-info" role="alert"></div>
```

#### Alert warning
Type `alert-warning` and press **`TAB`**
```html
<div class="alert alert-warning" role="alert"></div>
```

#### Alert danger
Type `alert-danger` and press **`TAB`**
```html
<div class="alert alert-danger" role="alert"></div>
```

#### Panel
Type `panel` and press **`TAB`**
```html
<div class="panel panel-default">
	<div class="panel-heading">
		<h3 class="panel-title"></h3>
	</div>
	<div class="panel-body">
		
	</div>
</div>
```

#### Accordion
Type `accordion` and press **`TAB`**
```html
<div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
	<div class="panel panel-default">
		<div class="panel-heading" role="tab" id="headingOne">
			<h4 class="panel-title">
				<a data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="true" aria-controls="collapseOne">Collapsible Group Item #1</a>
			</h4>
		</div>
		<div id="collapseOne" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
			<div class="panel-body">
				Panel 1 body....
			</div>
		</div>
	</div>
	<div class="panel panel-default">
		<div class="panel-heading" role="tab" id="headingTwo">
			<h4 class="panel-title">
				<a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">Collapsible Group Item #2</a>
			</h4>
		</div>
		<div id="collapseTwo" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
			<div class="panel-body">
				Panel 2 body....
			</div>
		</div>
	</div>
	<div class="panel panel-default">
		<div class="panel-heading" role="tab" id="headingThree">
			<h4 class="panel-title">
				<a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseThree" aria-expanded="false" aria-controls="collapseThree">Collapsible Group Item #3</a>
			</h4>
		</div>
		<div id="collapseThree" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
			<div class="panel-body">
				Panel 3 body....
			</div>
		</div>
	</div>
</div><!-- .panel-group -->
```

#### Breadcrumb
Type `breadcrumb` and press **`TAB`**
```html
<ol class="breadcrumb">
	<li><a href="#">Home</a></li>
	<li><a href="#">Library</a></li>
	<li class="active">Data</li>
</ol>
```

#### Carousel
Type `carousel` and press **`TAB`**
```html
<div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
	<ol class="carousel-indicators">
		<li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
		<li data-target="#carousel-example-generic" data-slide-to="1"></li>
		<li data-target="#carousel-example-generic" data-slide-to="2"></li>
	</ol>
	<div class="carousel-inner" role="listbox">
		<div class="item active">
			<img src="http://placehold.it/900x500" alt="">
			<div class="carousel-caption">
				Caption 1
			</div>
		</div>
		<div class="item">
			<img src="http://placehold.it/900x500" alt="">
			<div class="carousel-caption">
				Caption 2
			</div>
		</div>
		<div class="item">
			<img src="http://placehold.it/900x500" alt="">
			<div class="carousel-caption">
				Caption 3
			</div>
		</div>
	</div>
	<a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
		<span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
		<span class="sr-only">Previous</span>
	</a>
	<a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
		<span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
		<span class="sr-only">Next</span>
	</a>
</div><!-- .carousel -->
```

