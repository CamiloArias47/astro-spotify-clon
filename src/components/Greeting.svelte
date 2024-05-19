<script lang="ts">
  const currentTime = new Date()
  const currentHour = currentTime.getHours()

  let greeting = ""

  if(currentHour > 12){
    greeting = "Buenos días"
  }
  else if(currentHour < 18){
    greeting = "Buenas Tardes"
  }
  else{
    greeting = "Buenas Noches"
  }
</script>

<style>
    .greetings{
		color: white;
	}
</style>

<h1 class="greetings text-4xl font-bold">{greeting}</h1>