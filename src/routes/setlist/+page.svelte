<script>
	let selected = 1;
</script>

<div class="container flex flex-col justify-center text-center">
	<section class="lineup-section">
		<h1 class="text-3xl font-bold mb-5">lineup</h1>
		<p class="text-xl font-bold">PSAT (Pure Sound Audio Team)</p>
		<p class="text-xl font-bold">백색왜성</p>
		<p class="text-xl font-bold">밴드 파수꾼</p>
	</section>
	<div class="setlist-section">
		<h1 class="text-3xl font-bold mt-10">Set List</h1>
		<div class="overflow-x-auto">
			<div class="tabs">
				<a
					href="#"
					class="tab tab-lg tab-lifted {selected === 1 ? 'tab-active' : null}"
					on:click={() => (selected = 1)}>PSAT</a
				>
				<a
					href="#"
					class="tab tab-lg tab-lifted {selected === 2 ? 'tab-active' : null}"
					on:click={() => (selected = 2)}>백색왜성</a
				>
				<a
					href="#"
					class="tab tab-lg tab-lifted {selected === 3 ? 'tab-active' : null}"
					on:click={() => (selected = 3)}>파수꾼</a
				>
			</div>
			{#if selected === 1}
				<table class="table w-full table-zebra">
					<!-- head -->
					<thead>
						<tr>
							<th>곡순</th>
							<th>가수</th>
							<th>곡명</th>
						</tr>
					</thead>
					<tbody>
						<!-- row 1 -->
						<tr>
							<th>1</th>
							<td>유다빈밴드</td>
							<td>Letter</td>
						</tr>
						<!-- row 2 -->
						<tr>
							<th>2</th>
							<td>유다빈밴드</td>
							<td>Letter</td>
						</tr>
						<!-- row 3 -->
						<tr>
							<th>3</th>
							<td>유다빈밴드</td>
							<td>Letter</td>
						</tr>
						<!-- row 4 -->
						<tr>
							<th>4</th>
							<td>유다빈밴드</td>
							<td>Letter</td>
						</tr>
					</tbody>
				</table>
			{:else if selected === 2}
				<div class="overflow-x-auto">
					<table class="table w-full table-zebra">
						<!-- head -->
						<thead>
							<tr>
								<th>곡순</th>
								<th>가수</th>
								<th>곡명</th>
							</tr>
						</thead>
						<tbody>
							<!-- row 1 -->
							<tr>
								<th>1</th>
								<td>슈퍼</td>
								<td>마리오</td>
							</tr>
							<!-- row 2 -->
							<tr>
								<th>2</th>
								<td>슈퍼</td>
								<td>마리오</td>
							</tr>
							<!-- row 3 -->
							<tr>
								<th>3</th>
								<td>슈퍼</td>
								<td>마리오</td>
							</tr>
							<!-- row 4 -->
							<tr>
								<th>4</th>
								<td>슈퍼</td>
								<td>마리오</td>
							</tr>
						</tbody>
					</table>
				</div>
			{:else if selected === 3}
				<div class="overflow-x-auto">
					<table class="table w-full table-zebra">
						<!-- head -->
						<thead>
							<tr>
								<th>곡순</th>
								<th>가수</th>
								<th>곡명</th>
							</tr>
						</thead>
						<tbody>
							<!-- row 1 -->
							<tr>
								<th>1</th>
								<td>주호</td>
								<td>내가 아니라도</td>
							</tr>
							<!-- row 2 -->
							<tr>
								<th>2</th>
								<td>주호</td>
								<td>내가 아니라도</td>
							</tr>
							<!-- row 3 -->
							<tr>
								<th>3</th>
								<td>주호</td>
								<td>내가 아니라도</td>
							</tr>
							<!-- row 4 -->
							<tr>
								<th>4</th>
								<td>주호</td>
								<td>내가 아니라도</td>
							</tr>
						</tbody>
					</table>
				</div>
			{/if}
		</div>
	</div>

	<div class="flex gap-12 mt-12 sm:flex-col">
		<div class="indicator">
			<span class="indicator-item badge badge-secondary">99+</span>
			<button class="btn">inbox</button>
		</div>

		<div class="indicator">
			<span class="indicator-item badge badge-secondary" />
			<div class="grid w-32 h-32 bg-base-300 place-items-center">content</div>
		</div>
	</div>
</div>
<div class="text-sm breadcrumbs mt-12">
	<ul>
		<li>
			<a href="#">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					class="w-4 h-4 mr-2 stroke-current"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
					/></svg
				>
				Home
			</a>
		</li>
		<li>
			<a href="#">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					class="w-4 h-4 mr-2 stroke-current"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
					/></svg
				>
				Documents
			</a>
		</li>
		<li>
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				viewBox="0 0 24 24"
				class="w-4 h-4 mr-2 stroke-current"
				><path
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					d="M9 13h6m-3-3v6m5 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"
				/></svg
			>
			Add Document
		</li>
	</ul>
</div>
