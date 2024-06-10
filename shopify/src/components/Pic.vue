<template>
     <div class="image-container">
        <div class="big">
          <div class="product-detail">
            <div>
              <p style="font-size: 16px; font-weight: bold;">Fauxia Sport</p>
              <p style="font-size: 14px; font-weight: light;">Running Shoes</p>
            </div>
            <p style="font-size: 17px;">50$</p>
          </div>
        </div>
        
        <div >
          <div class="small">
            <div class="product-detail">
            <div>
              <p style="font-size: 16px; font-weight: bold;">Fauxia Sport</p>
              <p style="font-size: 14px; font-weight: light;">Running Shoes</p>
            </div>
            <p style="font-size: 17px;">50$</p>
          </div>
          </div>
          <div class="small">
            <div class="product-detail">
            <div>
              <p style="font-size: 16px; font-weight: bold;">Fauxia Sport</p>
              <p style="font-size: 14px; font-weight: light;">Running Shoes</p>
            </div>
            <p style="font-size: 17px;">50$</p>
          </div>
          </div>
        </div>
    </div>
</template>

<style scoped>
    
.small{
  width: 297px;
  height: 49%;
  background-size: 110%;
  background-position: center;
  box-shadow: 0 10px 10px 0 rgba(0, 0, 0, .25);
  margin-bottom: 1em;
  border-radius: 6px;
  cursor: pointer;
  display: flex;
  justify-content: center;
  align-items: flex-end;
  transition: all 300ms;
}

.small:hover{
  background-size: 130%;
}

.small:hover .product-detail{
  transform: translateY(-0.3em);
}

.small:first-child{
  background-image: url(/1.jpg);
}
.small:last-child{
  background-image: url(/2.jpg);
}
.product-detail{
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-inline:1em ;
  box-sizing: border-box;
  width: 266px;
  height: 77px;
  background-color: white;
  border-radius: 4px;
  margin-bottom: 1em;
  transition: all ease-in-out 200ms;
}


.image-container{
  height: 490px;
  display: flex;
  gap: 10px;
}

.big{
  display: flex;
  justify-content: center;
  align-items: flex-end;
  height: 100%;
  margin-inline: 1em;
  width:  297px;
  background-image: url(/Rectangle\ 1.png);
  background-position: center;
  background-size: 100%;
  border-radius: 6px;
  box-shadow: 0 10px 10px 0 rgba(0, 0, 0, .25);
  cursor: pointer;

  transition: all ease-in-out .3s;
}

.big:hover .product-detail{
  margin-bottom: 1.5em;
}

.big:hover{
  background-size: 110%;
}

</style>