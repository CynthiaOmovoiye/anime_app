<template>
    <div class="card">
        <a href="#" target="_blank">
            <img src="https://via.placeholder.com/150x250" alt="image">
            <h3>Naruto</h3>
        </a>
    </div>
</template>

<style lang="scss" scoped>
.card{
    width: 33%;
    max-width: 33%;
    flex: 1 1 33%;
    margin-bottom: 16px;
    padding: 0 8px;

    img{
        width: 100%;
        height: 400px;
        border-radius: 16px;
        object-fit: cover;
        box-shadow: 0px 4px 8px rgba($color: #000000, $alpha: 0.15);
        transition: 0.4s;

    }
    h3{
        padding: 16px;
        color: #313131;
        transition: 0.4s;
    }
    &:hover{
        img{
transform: scale(1.05);
        }
        h3{
            color: #24c444
        }
        
    }
}

</style>