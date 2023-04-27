<script>
	import poster from '../images/poster.jpg';
</script>

<div class="container flex flex-col justify-center items-center text-center">
	<div class="card w-96 bg-base-100 shadow-xl image-full">
		<figure><img src={poster} alt="Shoes" /></figure>
		<div class="card-body">
			<h2 class="card-title font-bold">'병목현상(甁目現象)'</h2>
			<p>넓은 길이 갑자기 좁아지면서 일어나는 정체 현상</p>
			<p>
				이번 공연 ‘병목현상’에서 들려드리는 곡들이 다소 생소할 수 있기에 여러분께 전해지는 감동의
				노폭(路幅)이 좁을 수 있으리라 생각합니다. 그럼에도 불구하고, 언젠가 해소되는 교통체증처럼
				좁은 길을 헤치고 쾌감과 감동을 전해드릴 수 있도록 진심을 다하고자 하는 공연진의 의지를
				담아내었습니다.
			</p>
			<div class="card-actions justify-end">
				<button class="btn btn-primary">
					<a href="/survey">병목현상 예매하기</a>
				</button>
			</div>
		</div>
	</div>
	<!-- <div class="dropdown">
		<label tabindex="0" class="btn m-1">dropdown</label>
		<ul tabindex="0" class="dropdown-content menu p-2 shadow bg-base-100 rounded-box w-52">
			<li><a>Item 1</a></li>
			<li><a>Item 2</a></li>
		</ul>
	</div> -->
	<div>
		<h2 class="text-3xl mt-12 font-bold">공연안내</h2>
		<p class="text-2xl mt-6">일시</p>
		<p class="text-xl mt-2">2023년 4월 16일 일요일 18:00 ~ 21:30</p>
		<p class="text-2xl mt-6">장소</p>
		<p class="text-xl mt-2">001클럽 (서울특별시 마포구 와우산로 18길 20)</p>
		<p class="text-2xl mt-6">수용인원</p>
		<p class="text-xl mt-2">150명 / 전석 스탠딩</p>
		<p class="text-2xl mt-6">티켓</p>
		<p class="text-xl mt-2">8,000원</p>
	</div>
	<div class="flex gap-2 mt-4">
		<div class="badge">neutral</div>
		<div class="badge badge-primary">primary</div>
		<div class="badge badge-secondary">secondary</div>
		<div class="badge badge-accent">accent</div>
		<div class="badge badge-ghost">ghost</div>
	</div>
</div>
