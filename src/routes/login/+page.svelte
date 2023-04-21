<div class="alert alert-success shadow-lg">
	<div>
		<svg
			xmlns="http://www.w3.org/2000/svg"
			class="stroke-current flex-shrink-0 h-6 w-6"
			fill="none"
			viewBox="0 0 24 24"
			><path
				stroke-linecap="round"
				stroke-linejoin="round"
				stroke-width="2"
				d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
			/></svg
		>
		<span>Your purchase has been confirmed!</span>
	</div>
</div>
<div class="alert alert-error shadow-lg">
	<div>
		<svg
			xmlns="http://www.w3.org/2000/svg"
			class="stroke-current flex-shrink-0 h-6 w-6"
			fill="none"
			viewBox="0 0 24 24"
			><path
				stroke-linecap="round"
				stroke-linejoin="round"
				stroke-width="2"
				d="M10 14l2-2m0 0l2-2m-2 2l-2-2m2 2l2 2m7-2a9 9 0 11-18 0 9 9 0 0118 0z"
			/></svg
		>
		<span>Error! Task failed successfully.</span>
	</div>
</div>

<div class="alert alert-warning shadow-lg">
	<div>
		<svg
			xmlns="http://www.w3.org/2000/svg"
			class="stroke-current flex-shrink-0 h-6 w-6"
			fill="none"
			viewBox="0 0 24 24"
			><path
				stroke-linecap="round"
				stroke-linejoin="round"
				stroke-width="2"
				d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"
			/></svg
		>
		<span>Warning: Invalid email address!</span>
	</div>
</div>

<div class="hero bg-base-100">
	<div class="hero-content flex-col lg:flex-col">
		<div class="card flex-shrink-2 w-full max-w-sm shadow-xl bg-base-100">
			<div class="card-body">
				<div class="form-control">
					<label class="label">
						<span class="label-text">Email</span>
					</label>
					<input type="text" placeholder="email" class="input input-bordered" />
				</div>
				<div class="form-control">
					<label class="label">
						<span class="label-text">Password</span>
					</label>
					<input type="text" placeholder="password" class="input input-bordered" />
					<label class="label">
						<a href="#" class="label-text-alt link link-hover">Forgot password?</a>
					</label>
				</div>
				<div class="form-control mt-6">
					<!-- The button to open modal -->
					<label for="my-modal" class="btn btn-primary">Login</label>
				</div>
			</div>
		</div>
		<div class="text-center lg:text-center">
			<h1 class="text-5xl font-bold mt-12">Login now!</h1>
			<p class="py-6">
				Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem
				quasi. In deleniti eaque aut repudiandae et a id nisi.
			</p>
		</div>
	</div>
</div>

<!-- Put this part before </body> tag -->
<input type="checkbox" id="my-modal" class="modal-toggle" />
<div class="modal">
	<div class="modal-box">
		<h3 class="font-bold text-lg">Congratulations random Internet user!</h3>
		<p class="py-4">
			You've been selected for a chance to get one year of subscription to use Wikipedia for free!
		</p>
		<div class="modal-action">
			<label for="my-modal" class="btn">Yay!</label>
		</div>
	</div>
</div>
