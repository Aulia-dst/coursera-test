# coursera-test
Coursera test repository
<!doctype html>
<html lang="en">
<head>
	<title>Profil Album's Hotel</title>
	
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1 shrink-to-fit=no">
	
	<link rel="stylesheet" type="text/css" href="assets/css/bootstrap.css">
	<link rel="stylesheet" type="text/css" href="assets/css/bootstrap.min.css">
	
	<script type="text/javascript" src="assets/js/jquery.min.js"></script>
	<script type="text/javascript" src="assets/js/popper.js"></script>
	<script type="text/javascript" src="assets/js/bootstrap.min.js"></script>
</head>
<body>
	<div class="pt-3">
		<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
			<a class="navbar-brand m-auto" href="index.php">Album's</a>
			<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
			<span class="navbar-toggler-icon"></span>
			</button>
			
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav m-auto">
					<li class="nav-item">
						<a class="nav-link" href="index.php">Home</a>
					</li>
					<li class="nav-item active">
						<a class="nav-link" href="tentang.php">Tentang</a>
					</li>
					<li class="nav-item dropdown">
						<a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Galery</a>
						<div class="dropdown-menu" aria-labelledby="navbarDropdown">
							<a class="dropdown-item" href="suiteroom.php">Suite Room</a>							
							<a class="dropdown-item" href="presidential.php">Presidential Room</a>							
							<a class="dropdown-item" href="standart.php">Standart Room</a>							
							<div class="dropdown-divider"></div>							
							<a class="dropdown-item" href="superior.php">Superior Room</a>		
							<a class="dropdown-item" href="deluxe.php">Deluxe Room</a>						
							<a class="dropdown-item" href="junior.php">Junior Suite Room</a>	
						</div>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="lamanlogin.php" onclick="runPopup()">Pemesanan</a>
						<script>
							function runPopup(){
								window.alert("Anda Harus Login terlebih dahulu");						
							};
						</script>
					</li>
				</ul>
			</div>
			<div>
			<a href="lamanlogin.php" class="btn btn-outline-light text-light mr-1">Login</a>
			<a href="lamandaftar.php" class="btn btn-outline-light text-light">Daftar</a>
			</div>
		</nav>
	</div>
 </body>
