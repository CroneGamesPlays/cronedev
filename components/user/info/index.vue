<template>
	<div class="mb-3">
		<h2 class="font-bold text-xs text-zinc-800 dark:text-slate-300 leading-4 mb-2 uppercase">About Me</h2>

		<!-- userInfoBody -->
		<div class="whitespace-pre-line">
			<span class="inline-block">
				<img src="~/assets/icons/transgender-flag.svg" alt="transgender-flag" class="w-5 h-5 inline-block align-bottom" draggable="false" />
			</span>
			{{ ' She/Her · ' }}
			<external-link href="https://www.16personalities.com/infp-personality" text="INFP-T" />{{ ' · 24\n' }}

			<span class="inline-block">
				<img src="~/assets/icons/frame-photo.svg" alt="frame-photo" class="w-5 h-5 inline-block align-bottom" draggable="false" />
			</span>
			{{ ' Avatar: ' }}
			<external-link href="https://twitter.com/Felipe81063023" text="@Felipe81063023" />
			{{ ' · Banner: ' }}
			<external-link href="https://tenor.com/es/ver/yu-otasaka-charlotte-anime-gif-11426452" text="Yu Otasaka Charlotte GIF" />
			{{ '\n\n' }}

			<span class="inline-block">
				<img
					src="~/assets/icons/small-blue-diamond.svg"
					alt="small-blue-diamond"
					class="w-5 h-5 inline-block align-bottom"
					draggable="false"
				/>
			</span>
			{{ ' ' }}
			<external-link href="https://github.com/CroneGamesPlays/cronedev" text="Crone" />{{ "'s Project Owner\n" }}

			<span class="inline-block">
				<img
					src="~/assets/icons/small-blue-diamond.svg"
					alt="small-blue-diamond"
					class="w-5 h-5 inline-block align-bottom"
					draggable="false"
				/>
			</span>
			{{ ' ' }}
			<external-link href="https://github.com/discordjs" text="Discord.js" />{{ ' Programador Dev & Administrador\n' }}

			<span class="inline-block">
				<img
					src="~/assets/icons/small-blue-diamond.svg"
					alt="small-blue-diamond"
					class="w-5 h-5 inline-block align-bottom"
					draggable="false"
				/>
			</span>
			{{ ' ' }}
			<external-link href="https://github.com/javascript" text="JavaScript & HTML" />{{ "'s Programador \n" }}
		</div>
	</div>
</template>
