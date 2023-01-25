<script>
    import About from "./about.svelte";
    import Footer from "./footer.svelte";
    import Nav from "./nav.svelte";
  function handleClick() {
    console.log("Button clicked");
  }
  let url ='';
  let error = '';
  let data = null;
let key="AIzaSyA3CaJH8AXwk4hUpiYdbRuyESLZ9lpXrx8";
  let display = false;

  function inputurl(event) {
    url = event.target.value;
    console.log(url)
  }

  async function fetchdata(event) {
    event.preventDefault();
    validateUrl(url);
    if (error) {
      alert(error);
    } else {

     await  fetch('https://www.googleapis.com/pagespeedonline/v5/runPagespeed?url='+url).then(response => {
        return response.json();
      }).then(data => {
        console.log(data);
      data = JSON.stringify(data);
      alert('Displaying on the Div');
        document.getElementById("resultJson").innerText =data;
      });
      alert('success line no 45');
      



    }
  }



  function validateUrl(value) {
    if (!value.match(/^(https?:\/\/)/)) {
      error = 'Please enter a valid URL';
    } else {
      error = '';
      
    }
  }

  
 
  console.log(url)

</script>



<main>
 <Nav></Nav>

<div class="heading2">
  <h3> Enter your web address in the box to get started</h3>
</div>


<div class="main">
  <form action="">
    <label for="url" class="link"></label>
    <!-- <input type="url" name="url" id="url" placeholder="  or IP address"> -->
    <input type="url" id="url" bind:value={url} on:input={inputurl} placeholder="Please enter valid url like  https://example.com">
    <span class="enter"></span>
  

    <button type="submit" on:click={fetchdata}>Submit</button>
    
    <div class="data">
      
      
      {#if data!=null}
      {data.id}
      this is data
      {/if}
      </div>
      <div id="resultJson">
        <div class="cards">
          <div class="card card-1">
            <p id="name1">Captcha ??</p>
            <div id="captcha1">
              
            </div>
          </div>
          <div class="card card-2">
            <p id="name2">Any Error Message ??</p>
            <div id="captcha2">
            </div>
          </div>
          <div class="card card-3">
            <p id="name3">Captcha ??</p>
            <div id="captcha3">
            </div>
          </div>
          <div class="card card-4">
            <p id="name4">Captcha ??</p>
            <div id="captcha4">
            </div>
          </div>
          <div class="card card-5">
            <p id="name5">Captcha ??</p>
            <div id="captcha5">
            </div>
          </div>
          <div class="card card-1">
            <p id="name1">Captcha ??</p>
            <div id="captcha6">
            </div>
          </div>
      
      
      </div>
      </div>
      
      <br>
      <div id="resultJson" style="background-color:brown ;width:100%" >
      
      </div>
    
  > 
    
  </form>
</div>

  


<Footer></Footer>
</main>
<!-- html ends over here -->

<!-- Styling starts from here -->

<style>

  .main{
    text-align: center;
    /* position: ; */
    margin: 100px;
    background-color: #f2eee3;
  
  }
  .link{
    position: absolute;
    left: 25%;
    top: 10px;
    font-weight: 200;
    color: #cecece ;
    transition: all 0.5s ease;
    pointer-events: none;
  }

  input{
    padding: 25px;
    width: 50%;
    border: 2px solid rgb(242, 242, 247);
    border-radius: 5px;
    text-align: center;
    height: 8px;
    
  }
  .heading{
    max-width: 100%;
    padding-top: 40px;
    padding-bottom: 40px;
  }
  h2{
    padding-top: 40px;
  }
  h2{
    justify-content: center;
    text-align: center;
    text-decoration: none;
    color: #f46d13;
  }
  h3{
    justify-content: center;
    text-align: center;
    text-decoration: none;
    color: #f46d13;
    padding-top: 30px;
  }

  button {
    display: block;
    position: relative;
    background-color: #8B2500;
    color: #FFFFFF;
    padding-top: 12px;
    padding: 14px 20px;
    margin: auto;
    margin-top: 12px;
    border: 2px;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1.2em;
    transition: background-color 0.2s ease-in;
  }
  button:hover {
    background-color: #8B1A1A;
  }

/* Navigation bar */


/* *******************************************************************************Navigation bar ends**************************************************** */




</style>
