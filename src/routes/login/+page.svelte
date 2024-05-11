<script>
    import "./login.css";

		function openMessageBox() {
			// Afficher un message
			const email = 'votre@email.com'; // Remplacez par l'adresse email souhaitée
			const message = `Envoyer un email à cette adresse ${email} en donnant votre adresse mail.`;
			alert(message);

			// Rediriger l'utilisateur vers une autre page si nécessaire
			// window.location.href = '/votre-page'; // Remplacez 'votre-page' par le chemin de la page vers laquelle vous souhaitez rediriger

			// Vous pouvez également utiliser une boîte de dialogue personnalisée avec un bouton OK

			const confirmation = confirm(message);
			if (confirmation) {
				// L'utilisateur a cliqué sur OK, effectuer une action supplémentaire si nécessaire
			}

		}


</script>

<section class="vh-100 gradient-custom">
	<div class="container py-5 h-100">
		<div class="row d-flex justify-content-center align-items-center h-100">
			<div class="col-12 col-md-8 col-lg-6 col-xl-5">
				<div class="card bg-dark text-white" style="border-radius: 1rem;">
					<div class="card-body p-5 text-center">

						<div class="mb-md-5 mt-md-4 pb-5">

							<h2 class="fw-bold mb-2 text-uppercase">Login</h2>
							<p class="text-white-50 mb-5">Please enter your login and password!</p>

							<div data-mdb-input-init class="form-outline form-white mb-4">
								<input type="email" id="typeEmailX" class="form-control form-control-lg" />
								<label class="form-label" for="typeEmailX">Email</label>
							</div>

							<div data-mdb-input-init class="form-outline form-white mb-4">
								<input type="password" id="typePasswordX" class="form-control form-control-lg" />
								<label class="form-label" for="typePasswordX">Password</label>
							</div>

<!--							<p class="small mb-5 pb-lg-2"><a class="text-white-50" href="#!">Forgot password?</a></p>-->

							<p class="small mb-5 pb-lg-2">
								<a class="text-white-50" href="#" onclick="openMessageBox()">Forgot password?</a>
							</p>

							<button data-mdb-button-init data-mdb-ripple-init class="btn btn-outline-light btn-lg px-5" type="submit">Login</button>

							<div class="d-flex justify-content-center text-center mt-4 pt-1">
								<a href="#!" class="text-white"><i class="fab fa-facebook-f fa-lg"></i></a>
								<a href="#!" class="text-white"><i class="fab fa-twitter fa-lg mx-4 px-2"></i></a>
								<a href="#!" class="text-white"><i class="fab fa-google fa-lg"></i></a>
							</div>

						</div>

						<div>
							<p class="mb-0">Don't have an account? <a href="/singup" class="text-white-50 fw-bold">Sign Up</a>
							</p>
						</div>

					</div>
				</div>
			</div>
		</div>
	</div>
</section>

