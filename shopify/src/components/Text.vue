<template>
    
        <div class="text-container">
        <h1 class="hero-text">
          Quality apparel <br> without the price tag
        </h1>
        <p class="sub-title">
          No need to spend $xxx  just for the name’s sake. <br> Our Premium apparel is made from the same <br> stuff 
        </p>

        <div class="call-to-action">
          <button class="pca">Browse our collection</button>
          <div class="sca">
            spring '23 Collection
          </div>
        </div>
        <div class="message-box">
          <img src="/stars.png" alt="">
          <h1 >50K</h1>
          <p style="font-size: 15px;">We’re proud to announce that we  now employ a <br> workforce of over <strong>50,000</strong> it’s  all possible because <br> of you</p>
        </div>
      </div>
    
</template>

<style scoped>
    
.message-box h1{
  font-weight: normal;
  margin-right: .5em;
  font-size: 35px;
  transform: translateY(-10px);
}

.message-box{
  margin-top: 2em;
  padding: 2em 1em;
  position: relative;
  border: solid 1px black;
  border-radius: 6px;
  width: 500px;
  height: 122px;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  align-items: center;
}

.message-box img{
  position: absolute;
  left: -30px;
  top: -10px;
}





.call-to-action{
  margin-top: 3em;
  display: flex;
  align-items: center;
  justify-content: flex-start;

}
.sca{
  position: relative;
  font-family: Poppins;
  font-size: 18px;
  cursor: pointer;
  text-decoration: none;
  transition: all 300ms ease-in-out;
}

.sca::after{
  content: '';
  position: absolute;
  width: 20px;
  height: 1px;
  right: -27px;
  top: 50%;
  background: #000;
}
.sca::before{
  content: '>';
  position: absolute;
  font-size: 20px;
  right: -27px;
}

.sca::after,.sca::before{
  transition: all 300ms ease-in-out;
}
.sca:hover::after,.sca:hover::before{
  right: -35px;
}

.sca:hover{
  text-decoration: underline;
}

.pca{
  cursor: pointer;
  font-size: 18px;
  font-weight: bold;
  background: var(--btn-color);
  padding: .5em 1em;
  border: none;
  border-radius: .2em;
  margin-right: 25px;
}

.pca:hover{
  background-color: #DACDBF;
}

.hero-text{
  font-family: Playfair Display;
  font-weight: normal;
  font-size: 52px;
}

.sub-title{
  font-family: Poppins;
  font-size: 18px;
  color: #585858;
  margin-top: 1rem;
}


</style>