<main>
	<h1>Sveltekit Template</h1>
	<h2>A sveltekit bare-bones starter template.</h2>

	<p>What batteries are in the box?</p>
	<b>Included is:</b>
	<ul>
		<li>Tailwind Css</li>
		<li>Typescript</li>
		<li>Svelte</li>
		<li>Eslint</li>
		<li>Pretty</li>
	</ul>
</main>

<main>
	<h1>Stylling / Sass</h1>
	<span>
		The use of Tailwind classes is moved into the style tag, using the <code>@apply</code> rule to use
		Tailwind classes
	</span>
	<b>In example</b>
	<div class="code-preview">
		<span>app.sass</span>
		<div class="code">
			<div class="selector">@apply</div>
			flex flex-col w-fit max-w-lg m-auto items-center
		</div>
	</div>
</main>

<style lang="sass">
.code-preview
    @apply flex flex-col items-start gap-1.5
    span
        @apply m-0 px-3 py-1.5 rounded bg-indigo-500 text-white font-semibold

code
    font-family: 'Roboto Mono'
    @apply text-black bg-gray-200 p-1 px-2 rounded-md text-sm

.code
    @apply px-3 py-4 bg-gray-800 text-white rounded text-indigo-300 font-semibold
    .selector
        @apply text-base text-base text-emerald-400 w-fit inline-block

main
    @apply flex flex-col w-fit max-w-lg m-auto items-center gap-2 my-20 border rounded-md px-8 py-10 shadow-md
    h1
        @apply text-3xl font-bold
    h2
        @apply text-lg text-orange-400
    p
        @apply text-base px-5 py-2 rounded-md text-white bg-blue-600 mt-2 font-semibold mt-3
    b
        @apply text-slate-600 text-lg mt-3 border-b
    ul
        @apply text-center
        li
            @apply my-1 text-base font-semibold text-slate-800 p-1
    span
        @apply py-1 mt-1
</style>
