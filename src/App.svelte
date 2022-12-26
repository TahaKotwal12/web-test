<script>

</script>

<main>
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
  <div class="navigation">
    <a href="WEBTEST" class="logo">webtest</a>
    <a class="active" href="#home">Home</a>
    <a href="#news">News</a>
    <a href="#contact">Contact</a>
    <a href="#about">About</a>
    
  </div>
  

<h1>

Home page content

</h1>



<h1>


Serach box

</h1>
  <div class="footer-section">
    <div class="footer-item">
      <h2>webtest</h2>
      <br>
    <p><a href="About-us">About us</a></p>
    <p><a href="Contact US">Contact us</a></p>
    <p><a href="Get started">Get started</a></p>
    <p><a href="Our services">Our services</a></p>
    </div>
    <div class="footer-item">
      <h2>About webtest</h2>
      <br>
      <p>WebPerform was developed as a tool for customers <br>
        to easily  test the performance of their webpages. <br>
        Want to work with us? Check out our Careers page</p>

    </div>

    <div class="footer-item social">
      <h2>Follow us</h2>
      <br>
      <ul>
        <li><i class="fa-brands fa-instagram"></i></li>
        <li><i class="fa-brands fa-linkedin-in"></i></li>
        <li><i class="fa-brands fa-youtube"></i></li>
        <li><i class="fa-brands fa-twiter"></i></li>
      </ul>
    </div>
  </div>
</main>











<style>

/* Navigation bar */
.navigation{
  max-width: 100%;
  background-color: #333;
  overflow: hidden;
}
 
.navigation a{
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  transition: 0.4s;
}
.navigation a:hover{
  color: blue;

}

/* *******************************************************************************Navigation bar ends**************************************************** */



.footer-section {
  width: 100%;
  display: flex;
  color: white;
  justify-content: space-around;
  flex-wrap: wrap;
  padding: 1rem 0;
  background-color: #333;
}
.footer-section h2{
  margin-bottom: 1rem;
  position:relative;

}

.footer-section h2::after{
  content: '';
  width: 3rem;
  height: .2rem;
  background:#e65b00;
  position: absolute;
  top: 2.5rem;
  left: 0;

}

.footer-section p{
  transition: all .2s linear;
  margin-bottom: .6em;
}
a{
  color: white;
  text-decoration: none;
  cursor: pointer;
  

}
.footer-section p:hover{
  transition: all .2s linear;
  transition: translateX(4px);
}

.footer-section a:hover{
  color: #f46d13;

}
.footer-item{
  margin:1rem;

}

.footer-item ul{
  display: flex;
  justify-content: space-around;
  list-style: none;

}
.footer-item li{
  margin-right: 1rem;
}
.social ul li {
  font-size: 1.2rem;
  cursor: pointer;
  transition: all .2s linear;
}
.social ul li:hover{
  color:  #e65b00;
  transform: scale(1.1);
  transition: all .2s linear;
}
@media screen and (max-width: 320px){
  .footer-section{
    flex-direction: column;
    justify-content: flex-start;
   padding-left: 2rem; 
  }
}
</style>
