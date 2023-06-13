<template>
<div>
    <section class="card">
        <div class="container">
            <div class="row g-5">
                <div class="col-md-3" v-for="(burger,index) in 50 " :key="index">
                    <div class="card" style="width: 100%">
                       <div class="image-body">
                        <img src="https://cdn.pixabay.com/photo/2012/04/14/15/37/cheeseburger-34314_640.png" class="card-img-top" alt="...">
                       </div>
                        <div class="card-body">
                            <h5 class="card-title">BURGER SET</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

</div>
</template>

<script setup>

</script>

<style scoped>
img {
    filter: grayscale() ;
    transition: 1s;
    
}

img:hover {
    filter: none;
    transform: scale(2);
}

.image-body {
    overflow: hidden;
}
</style>
