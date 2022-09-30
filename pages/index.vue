<template>
	<section class="body-font">
		<div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
			<div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
				<h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900 dark:text-gray-100">CroneGamesPlays</h1>
				<p class="mb-8 leading-relaxed">
					Olá, prazer em conhecê-lo, me chamo Crone, sou um desenvolvedor de bots para o Discord, programo usando a linguagem NodeJS (JavaScript).
				</p>
				<div class="flex justify-center">
					<button-link href="https://github.com/CroneGamesPlays" text="GitHub" />
					<button-link href="https://twitter.com/Felipe81063023" text="Twitter" class="ml-2" />
				</div>
			</div>

			<user-card />
		</div>
	</section>
</template>
