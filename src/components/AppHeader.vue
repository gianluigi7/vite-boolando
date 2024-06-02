<script>
export default {
    name: 'AppHeader'
};
</script>

<template>
    <header>

        <div class="contenitore">
            <div class="row align-c">
                <div class="col33">
                    <div><button class="tlb">Donna</button>
                        <button class="tlb">Uomo</button>
                        <button class="tlb">Bambini</button>
                    </div>
                </div>
                <div class="col33 text-center">
                    <img src="./img/boolean-logo.png" href="Boolean" class="Boolean">
                </div>
                <div class="col33 text-right">
                    <div><button class="trb">1</button> 
                        <button class="trb">2</button> 
                        <button class="trb">3</button> 
                    </div>
                </div>
            </div>
        </div>
    </header>
        
    </template>

<style>
*{
padding: 0;
margin: 0;
box-sizing: border-box;
}
header{
    position: fixed;
    top: 0;
    left: 0;
    background-color: rgb(255, 102, 0);
    width: 100%;
    padding: 20px 0;
    z-index: 15;
}
.contenitore{
    max-width: 1200px;
    margin: 0 auto;
}   
.align-c{
    align-items: center;
    
 }
 .align-v{
    vertical-align: middle;
  }

 .col33{
    width: calc(100% / 3 - 20px);
    margin: 0 10px;
    
 }
 .row{
    display: flex;
    flex-wrap: wrap;
 }
  

 .text-center{
    text-align: center;
 }
 .text-right{
    text-align: right;
  
 }
 header button {
    background-color: transparent;
    border: none;
    color: black;
    padding-right: 7px;
    font-weight: 600;
 }
 </style>