<style>
	h1, h2, h3, .center {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0.5em 0;
	}

  h2 {
    font-size: 2em;
  }

  .section-item h2 {
    font-weight: 700;
  }


	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}

  .section {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
  }

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

<h1>Skills</h1>
<div class="section">
  <div class="section-item" style="background-image: url(/laravel.png)">
    <div class="section-title">
      <h2>Laravel</h2>
      <h3>5 years</h3>
    </div>
    <!-- <div class="examples">
      <a href="https://www.agedcareguide.com.au/" class="example">
        Aged Care Guide
      </a>
      <a href="https://www.agedcareguide.com.au/" class="example">
        Disability Support Guide
      </a>
    </div> -->
  </div>

  <div class="section-item" style="background-image: url(/vue.png)">
    <div class="section-title">
      <h2>VueJS</h2>
      <h3>4 Years</h3>
    </div>
    <!-- <div class="examples">
      <a href="https://www.agedcareguide.com.au/" class="example">
        Aged Care Guide
      </a>
      <a href="https://www.agedcareguide.com.au/" class="example">
        Disability Support Guide
      </a>
    </div> -->
  </div>

  <div class="section-item" style="background-image: url(/svelte.png)">
    <div class="section-title">
      <h2>Svelte</h2>
      <h3>2 Years</h3>
    </div>
    <!-- <div class="examples">
      <a href="https://recommend.ttp.sh/" class="example">
        Spotify Song Recommendations
      </a>
      <a href="https://github.com/thattomperson/ttp.sh" class="example">
        This site
      </a>
    </div> -->
  </div>

  <div class="section-item" style="background-image: url(/aws.png)">
    <div class="section-title">
      <h2>AWS</h2>
      <h3>6 Years</h3>
    </div>
    <!-- <div class="examples">
      <a href="https://www.agedcareguide.com.au/" class="example">
        Aged Care Guide
      </a>
    </div> -->
  </div>
</div>