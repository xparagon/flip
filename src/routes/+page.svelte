<script>
	import '../app.css';
	import Help from '../component/Help.svelte';
</script>

<div class="centered centered-row">
	<img src="/logo.png" alt="SNAKK MED MEG logo" style="width: 50vw" />
</div>

<div class="centered centered-column">1/3</div>

<div class="centered centered-column">
	<div>
		<big> Word </big>
	</div>
	<div>
		<big> Translation </big>
	</div>
</div>

<div class="centered centered-row">
	<div>not known</div>
	<div>-</div>
	<div>is known</div>
</div>

<Help />

<div class="centered centered-row">
	<small>
		<span>English</span>
		<span>-</span>
		<span>Ukranian</span>
		<span>-</span>
		<span>Arabic</span>
	</small>
</div>

<div class="centered centered-column">Score</div>
