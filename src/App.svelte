<script>
    import About from "./about.svelte";
    import Footer from "./footer.svelte";
    import Nav from "./nav.svelte";


</script>

<main>
 <Nav></Nav>

<div class="heading2">
  <h3> Enter your web address in the box to get started</h3>
</div>


<div class="main">
  <form action="">
    <label for="url" class="link"></label>
    <input type="url" name="url" id="url" placeholder=" Please enter valid url or IP address">
    <span class="enter"></span>
  </form>
</div>

  


<Footer></Footer>
</main>
<!-- html ends over here -->

<!-- Styling starts from here -->

<style>

  .main{
    text-align: center;
    position: center;
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

/* Navigation bar */


/* *******************************************************************************Navigation bar ends**************************************************** */




</style>
