<script>
	var nowDate = new Date();
	var eveningDate = new Date(nowDate.getFullYear(), nowDate.getMonth(), nowDate.getDate(), 20);
	var untilDate = eveningDate.getTime() - nowDate.getTime();
	var hours;
	var minutes;
	var seconds;
</script>

<main>
	<div class="wrapper">
		<h1>До вечера осталось: <br><span>{hours}:{minutes}:{seconds}</span></h1>
	</div>
</main>

<style>
</style>