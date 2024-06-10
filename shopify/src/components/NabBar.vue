<template>
    
    <div class="nav-bar">
      <img src="/logo.png" width="130px" height="130px" alt="">
      <ul>
        <li>HOME</li>
        <li>PRODUCTS</li>
        <li>GALLARY</li>
        <li>CONTACTS</li>
      </ul>
    </div>

</template>

<style scoped>
      .nav-bar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
  }
  ul{
    list-style-type: none;
    width: 50%;
    display: flex;
    justify-content: flex-end;
    flex-direction: row;
  }

  ul>li{
    margin-left: 4em;
    font-size: 17px;
    transform-origin: left;
    position: relative;
    cursor: pointer;
  }

  li::after{
    content: '';
    position: absolute;
    width: 100%;
    transform: scaleX(0);
    height: 2px;
    bottom: 0;
    left: 0;
    background-color: #646464;
    transform-origin: bottom right;
    transition: transform 0.25s ease-out;
  }
  
  li:hover::after,li:active::after{
    transform: scaleX(1);
    transform-origin: bottom left;
  }
</style>