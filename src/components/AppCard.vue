<script>
import products from '../partials_scss/db.json';
export default {
    name: 'AppCard',
    data() {
        return {
          products,
        }
    }
};
console.log(products);
</script>

<template>
    
    <div class="container">
        <ul>
            <li class="content">  <!-- v-for="(x, index) in this.products -->
                
                <img class="main-image" src="../assets/img/1.webp">
                <img class="hover-image" src="../assets/img/1b.webp">
                <div class="discount-label">-50%</div>
                <div class="sostenibilità">Sostenibilità</div>
                <div class="heart">&#10084;</div>
                <div class="lightgray">Levi's</div>
                <div><strong>RRELAXED FIT TEE UNISEX</strong></div>
                <div class="red">14.99 &euro; <span class="gray linea">29.99 &euro;</span></div>
            </li>
        </ul>
    </div>
</template>