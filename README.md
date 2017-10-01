<h1> Completed Accessibility Changes</h1>

- Added 'ALT' attribute tag
```html
  - Line 161, column 50, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/05/Champion-Pump.png"
  - Line 247, column 50, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/pumpfront.png"
  - Line 248, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/Full-Assembly.png"
  - Line 249, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/Pump12.png"
  - Line 250, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/pumptop.png"
  - Line 251, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/Housing.png"
  - Line 304, column 11, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/EPFlowChart.jpg"
  - Line 307, column 4, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/PumpTable.jpg"
  - Line 350, column 50, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/filterfrontEPC1.png"
  - Line 351, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/filterfrontepc2.png"
  - Line 352, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/filterback.png"
  - Line 353, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/filterGague.png"
  - Line 354, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/FilterControls.png"
  - Line 355, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2014/12/FilterRam.png"
  - Line 418, column 4, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/08/Bell-Filter-Front.jpg"
  - Line 437, column 50, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/08/Bell-Filter-Front.jpg"
  - Line 438, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/08/Bell-Filter-Back.jpg"
  - Line 439, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/08/Bell-Filter-Side.jpg"
  - Line 440, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/08/Bell-Filter-Panel-Inside.jpg"
  - Line 441, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/201...er-VFD-Standalone-Controller.jpg"
  - Line 543, column 50, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/08/10galRo.jpg"
  - Line 544, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/08/10galRobackTubes.png"
  - Line 545, column 47, img element, SRC = "https://elmirapump.com/wp-content/uploads/2016/08/Bell-Fitler-Panel-Outside.jpg"
```

- Added 'NOSCRIPT' tags
```html
    <noscript>
      <p>This page requires a JavaScript-enabled Broswer</p>
    </noscript>
```

- Added 'ALT' for INPUT tag
```html
    <input id="search2" type="submit" class="search-submit" value="" alt="Submit Search">
    <input id="search1" alt="Search Field" type="search" class="search-field" value="">
```

- Replaced 'PLACEHOLDER' for INPUT tag
```html
    <input id="search1" alt="Search Field" type="search" class="search-field" value="">
```

- Added BOOTSTRAP functionalities
```html
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```

- Added a Responsive Navigation Layout
```html
  <nav class="navbar navbar-inverse bg-inverse navbar-toggleable-md color-me">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand active">Elmira Pump Co Inc.</a>
      </div>
      <ul class="nav navbar-nav">
        <li class="active"><a href="https://elmirapump.com/">Home</a></li>
        <li><a href="https://elmirapump.com/index.php/about-us/">About Us</a></li>
        <li><a href="https://elmirapump.com/index.php/cart/">Cart</a></li>
        <li><a href="https://elmirapump.com/index.php/cart/">Checkout</a></li>
  			<li><a href="https://elmirapump.com/index.php/contact/">Contact Us</a></li>
  			<li><a href="https://elmirapump.com/index.php/sample-page/">Custom Project</a></li>
  			<li><a href="https://elmirapump.com/index.php/elmira-pump-shop-login/">Elmira Pump Shop Login</a></li>
  			<li><a href="https://elmirapump.com/index.php/my-account/">My Account</a></li>
  			<li><a href="https://elmirapump.com/index.php/shop/">Shop</a></li>
  			<li><a href="https://elmirapump.com/index.php/terms-conditions/">Terms &amp; Conditions</a></li>
  			<li><a href="https://elmirapump.com/index.php/shop-2/">Top Brands</a></li>
  			<li>
  				<form class="form-inline">
  					<input class="form-control mr-sm-2" type="text" alt="search">
  					<button class="btn btn-outline-success my-2 my-sm-0 color-button" type="submit">Search</button>
  				</form>
  			<li>
  		</ul>
  	</div>
  </nav>
```

- Updated CSS and Bootstrap layouts to make website more Responsive
