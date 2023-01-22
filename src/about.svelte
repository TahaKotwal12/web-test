<script>
 import About from "./about.svelte";
  
  import Footer from "./footer.svelte";
  import Nav from "./nav.svelte";
  
</script>
<main>
  <nav></nav>
  <body>
    <h1>About Us</h1>
    <div class="card-container">
      <div class="card">
        <img src="taha.jpg" alt="Team Member 1">
        <h2>Name: Taha Kotwal</h2>
        <p>About: Backend Developer</p>
        <a href="tahakotwal54@gmail.com">Gmail</a>
        <a href="https://www.linkedin.com/in/taha-kotwal-894b911b5">LinkedIn</a>
      </div>
      <div class="card">
        <img src="faisal.jpg" alt="Team Member 2">
        <h2>Name: Sayyed Faisal Ali</h2>
        <p>About: Backend Developer</p>
        <a href="fsali315@gmail.com">Gmail</a>
        <a href="https://www.linkedin.com/in/c0de-slayer">LinkedIn</a>
      </div>
      <div class="card">
      
        <img src="faizan.png" alt="Team Member 3">
        <h2>Name: Mohammed Faizan</h2>
        <p>About: Frontend Developer</p>
        <a href="mohammed.faizan11092@gmail.com">Gmail</a>
        <a href="url">LinkedIn</a>
      </div>
      <div class="card">
        <img src="aarohi.JPG" alt="Team Member 4">
        <h2>Name: Aarohi Panicker</h2>
        <p>About: Frontend Developer</p>
        <a href="aarohi.panicker.btech2021@situne.edu.in">Gmail</a>
        <a href="https://www.linkedin.com/in/aarohipanicker/">LinkedIn</a>
      </div>

    </div>
    <div class="card-container">
        <div class="card">
          <img src="shruti.jpeg" alt="Team Member 5">
          <h2>Name: Shruti Shukla</h2>
          <p>About: Frontend Developer</p>
          <a href="shrutishukla0952002@gmail.com">Gmail</a>
          <a href="https://www.linkedin.com/in/shruti-shukla-82a683218">LinkedIn</a>
        </div>
        <div class="card">
          <img src="akash.jpeg" alt="Team Member 6">
          <h2>Name: Akash Chowdhury</h2>
          <p>About: Frontend Developer</p>
          <a href="csonai2001@gmail.com">Gmail</a>
          <a href="https://www.linkedin.com/in/akash-chowdhury-409b8b25a">LinkedIn</a>
        </div>
        <div class="card">
          <img src="rudra.jpg" alt="Team Member 7">
          <h2>Name: Rudra shekhar Das</h2>
          <p>About: Frontend Developer</p>
          <a href="url">Gmail</a>
          <a href="url">LinkedIn</a>
        </div>
        <div class="card">
          <img src="amod.jpg" alt="Team Member 8">
          <h2>Name: Amod Nagbhidkar</h2>
          <p>About: Backend Developer</p>
          <a href="amodnagbhidkar08@gmail.com">Gmail</a>
          <a href="https://www.linkedin.com/in/amod-nagbhidkar-53381a21b">LinkedIn</a>
        </div>
  
      </div>
      <div class="card-container">
        <div class="card">
          <img src="taiyab.jpg" alt="Team Member 9">
          <h2>Name: Taiyab Lokhandwala</h2>
          <p>About: Frontend Developer</p>
          <a href="taiyablok22@gmail.com">Gmail</a>
          <a href="https://www.linkedin.com/in/taiyab-lokhandwala-a9a354249">LinkedIn</a>
        </div>
        <div class="card">
          <img src="dhruv.jpg" alt="Team Member 10">
          <h2>Name: Dhruv Kothari</h2>
          <p>About: Jane is a talented designer with a keen eye for detail. She has a passion for creating visually stunning websites that are easy to navigate.</p>
        </div>
        <div class="card">
          <img src="team-member-3.jpg" alt="Team Member 3">
          <h2>Name: John Doe</h2>
          <p>About: Jack is a creative developer who's specialize in creating interactive and dynamic web applications. He also has experience in machine learning and computer vision.</p>
        </div>
        <div class="card">
          <img src="team-member-4.jpg" alt="Team Member 4">
          <h2>Name: Jack Miller</h2>
          <p>About: Jack is a creative developer who's specialize in creating interactive and dynamic web applications. He also has experience in machine learning and computer vision.</p>
        </div>
  
      </div>
  </body>
</main>
<style>
body {
        background-color: black;
        color: white;
      }

      /* Define the styling for the header */
      h1 {
        font-size: 48px;
        font-weight: bold;
        text-align: center;
        margin-top: 50px;
      }

      /* Define the container for the cards */
      .card-container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin: 0 auto;
        width: 80%;
        padding: 20px;
    
      }

      /* Define the styling for the cards */
      .card {
        background-color: white;
        color: black;
        width: 25%;
        height: 350px;
        text-align: center;
        border-radius: 10px;
        box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.3);
        margin: 0 20px;
        
        
      }

      /* Define the styling for the images in the cards */
      .card img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        margin-top: 25px;
      }

      /* Define the hover styling for the cards */
      .card:hover {
        background-color: orange;
        color: white;
      }
</style>



