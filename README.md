# module2_soultion
<!DOCTYPE html>
<html>
<head>
<meta charest="utf-8">
<title>Our menue</title>
<style>

*{
	box-sizing: border-box;
}
h1{
	margin-bottom:15px;
}
p{
	border:1px solid black;
	background-color: #999999;
	margin-bottom:15px;
	width: 90%;
	hight: 150%;
	font-family: Helvetica;
	color: black;
}
.row{
	width:100%;
}

@media (min-width:992px){
  .col-lg-1, .col-lg-2, .col-lg-3{
  float: left;
  border:1px;
  }
  .col-lg-1{
  width: 33.33%
  }
  .col-lg-2{
  width: 66.66%
  }
  .col-lg-3{
  width: 99.99%
  }
}

@media(min-width:768px) and (min-width:991px){
	  .col-md-1, .col-md-2, .col-md-3{
  float: left;
  border:1px;
  }
  .col-md-1{
  width: 33.33%
  }
  .col-md-2{
  width: 66.66%
  }
  .col-md-3{
  width: 99.99%
  }
}
}
#p1{
	Width:33.33%;
}
#p2{
	Width:66.66%;
}
#p3{
	Width:100%;
}

</style>
</head>
<body>
<h1>Our Menu</h1>

<div class="row">
<div class="col-lg-4 col-md-4"><p>This is a parageraph for test</p></div>
<div class="col-lg-4 col-md-4"><p>This is a parageraph for test</p></div>
<div class="col-lg-4 col-md-4"><p>This is a parageraph for test</p></div>
</div>
</body>
</html>
