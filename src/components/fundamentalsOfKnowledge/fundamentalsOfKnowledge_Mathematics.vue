<template>
  <!-- Section: Icon Boxes -->
  <div>
  <section class="section section-icons black  center">
    <div class="container">
      <div class="row">
        <div class="col s12 m8">
          <div class="card-panel z-depth-5">
            <h4 class="left-align">Mathematics:</h4>
            <h5 class="left-align"> The Abstraction of Language</h5>
            <figure class="snip1543">
            <img src="../../assets/images/q2.gif" class="imglarge responsive">
              <figcaption>
                <p>
                  Fractal Eyes by Oscar H. Criner
                </p>
              </figcaption>
            </figure>
            <p class="left-align">
              Many people have wondered why mathematical scientists are very 
              often good musicians. I found the study of music, drama, and art 
              especially helpful in the study of science and mathematics.  
            </p>
            <p class="left-align">
             One secret to the study of mathematics is in the study of music.  
             The methods to which students of music are subjected train the 
             memory and enhance pattern recognition.  The study of mathematics 
             requires a great deal of pattern recognition. Indeed, the expression 
             "of the form" is repeated through mathematics.  
            </p>
          </div>
        </div>
        <div class="col s12 m4">
          <div class="card-panel z-depth-5">
            <p>
              <img src="../../assets/images/ElbertFCox.gif" class="responsive imglarge">
            </p>
            <p class="left-align">
              Elbert F. Cox, Ph.D. was the first black person in the world to 
              earn a doctorate in mathematics. I began my serious study of 
              mathematics under Professor Cox.
            </p>
            <p class="left-align">
              Professor Cox was an unusual teacher who taught me much more that 
              the mathematics. He wanted to develop a mathematical initiative in 
              students. Those who showed initiative received his utmost attention.  Those who merely sat in the class, got a lecture.  
            </p>
            <p class="left-align">
                <ol>
                  <li>
                    Tobias Dantzig,<i> Number the Language of Science</i>, 
                  </li>
                  <li>
                    Hugh Gray Leiber and Lillian Leiber,<i> The Education of T. C. 
                    Mits</i>, New York: W.W. Norton and Company, 1978
                  </li>
                  <li>
                    Hugh Gray Leiber and Lillian Leiber,<i> Infinity,</i> 
                    (A marvelous introduction to the calculus and the concept of 
                    measure, if you can find the book.)
                  </li>
                </ol>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
  </div>
</template>

<style scoped>
.imglarge{
  width: 100%;
  height: auto;
}

.snip1543 {
  background-color: #fff;
  color: #ffffff;
  display: inline-block;
  margin: 10px 5px;
  overflow: hidden;
  position: relative;
  text-align: left ;
  -webkit-transform: translateZ(0);
  transform: translateZ(0);
}

.snip1543 *,
.snip1543 *:before,
.snip1543 *:after {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  -webkit-transition: all 0.45s ease;
  transition: all 0.45s ease;
}

.snip1543 img {
  backface-visibility: hidden;
  max-width: 100%;
  vertical-align: top;
}

.snip1543:before,
.snip1543:after {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  content: '';
  background-color: black;
  opacity: 0.5;
  -webkit-transition: all 0.45s ease;
  transition: all 0.45s ease;
}

.snip1543:before {
  -webkit-transform: skew(30deg) translateX(-80%);
  transform: skew(30deg) translateX(-80%);
}

.snip1543:after {
  -webkit-transform: skew(-30deg) translateX(-70%);
  transform: skew(-30deg) translateX(-70%);
}

.snip1543 figcaption {
  position: absolute;
  top: 0px;
  bottom: 0px;
  left: 0px;
  right: 0px;
  z-index: 1;
  bottom: 0;
  padding: 25px 40% 25px 20px;
}

.snip1543 figcaption:before,
.snip1543 figcaption:after {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background-color: red;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.7);
  content: '';
  opacity: 0.5;
  z-index: -1;
}

.snip1543 figcaption:before {
  -webkit-transform: skew(30deg) translateX(-100%);
  transform: skew(30deg) translateX(-100%);
}

.snip1543 figcaption:after {
  -webkit-transform: skew(-30deg) translateX(-90%);
  transform: skew(-30deg) translateX(-90%);
}

.snip1543 p {
  opacity: 0;
  text-align: left;
  bottom: 5%;
}

.snip1543:hover p,
.snip1543.hover p {
  -webkit-transform: translateY(0);
  transform: translateY(0);
  opacity: 0.9;
  -webkit-transition-delay: 0.2s;
  transition-delay: 0.2s;
}

.snip1543:hover:before,
.snip1543.hover:before {
  -webkit-transform: skew(30deg) translateX(-20%);
  transform: skew(30deg) translateX(-20%);
  -webkit-transition-delay: 0.05s;
  transition-delay: 0.05s;
}

.snip1543:hover:after,
.snip1543.hover:after {
  -webkit-transform: skew(-30deg) translateX(-10%);
  transform: skew(-30deg) translateX(-10%);
}

.snip1543:hover figcaption:before,
.snip1543.hover figcaption:before {
  -webkit-transform: skew(30deg) translateX(-40%);
  transform: skew(30deg) translateX(-40%);
  -webkit-transition-delay: 0.15s;
  transition-delay: 0.15s;
}

.snip1543:hover figcaption:after,
.snip1543.hover figcaption:after {
  -webkit-transform: skew(-30deg) translateX(-30%);
  transform: skew(-30deg) translateX(-30%);
  -webkit-transition-delay: 0.1s;
  transition-delay: 0.1s;
}
</style>