<script>
import Section from '../components/Section.svelte'
</script>

<style>

   .section-item {
    display: flex;
    max-width: 28em;
    min-width: 20em;
    height: 300px;
    justify-content: space-around;
    flex-direction: column;
    background-size: contain;
    background-position: center;
    background-repeat: no-repeat;
  }
  .section-title {
    background: rgba(255,255,255,0.5);
    width: max-content;
    padding: 10px;
    margin: 0 auto;
  }

  .section-item h2 {
    font-weight: 700;
  }


	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}


  .examples {
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
  }

  .example {
    border-radius: 3px;
    box-shadow: 1px 1px 1px rgba(51,51,51,0.3);
    padding: 10px;
    background: white;
    margin-left: 5px;
  }

  .avatar {
    border-radius: 100%;
  }

</style>

<svelte:head>
	<title>Thomas Albrighton</title>
</svelte:head>

<div class="center">
  <img alt="Thomas Albrighton's Avatar" class="avatar" src="/photo.png" >
</div>
<h1>Thomas Albrighton</h1>
<h2>DevOps | SysAdmin | Solution Arichtect | Developer</h2>



<Section title="Skills">
  <div class="section-item" style="background-image: url(/laravel.png)">
    <div class="section-title">
      <h2>Laravel</h2>
      <h3>5 years</h3>
    </div>
  </div>

  <div class="section-item" style="background-image: url(/vue.png)">
    <div class="section-title">
      <h2>VueJS</h2>
      <h3>4 Years</h3>
    </div>
  </div>

  <div class="section-item" style="background-image: url(/svelte.png)">
    <div class="section-title">
      <h2>Svelte</h2>
      <h3>2 Years</h3>
    </div>
  </div>

  <div class="section-item" style="background-image: url(/aws.png)">
    <div class="section-title">
      <h2>AWS</h2>
      <h3>6 Years</h3>
    </div>
  </div>
</Section>

<Section title="Employment">
  <div class="section-item" style="background-image: url(/aws.png)">
    <div class="section-title">
      <h2>DPS Publishing</h2>
      <h3>DevOps | SysAdmin | Solution Arichtect | Developer</h3>
      <h3>Dec 2012 - Dec 2019</h3>
    </div>
  </div>
  <div class="section-item" style="background-image: url(/aws.png)">
    <div class="section-title">
      <h2>CATA Group</h2>
      <h3>Founder / CTO</h3>
      <h3>March 2016 - Ongoing</h3>
    </div>
  </div>
</Section>

<h1>Hobbies</h1>
<Section title="Hobbies">
  <div class="section-item" style="background-image: url(/honda.png)">
    <div class="section-title">
      <h2>Motorcycle Referbishing</h2>
    </div>
  </div>
  <div class="section-item" style="background-image: url(/aws.png)">
    <div class="section-title">
      <h2>DnD</h2>
    </div>
  </div>
  <div class="section-item" style="background-image: url(/aws.png)">
    <div class="section-title">
      <h2>Rocket League</h2>
    </div>
  </div>
  <div class="section-item" style="background-image: url(/aws.png)">
    <div class="section-title">
      <h2>Cooking / Baking</h2>
    </div>
  </div>
</Section>