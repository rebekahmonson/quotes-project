<template>
    <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="panel panel-default">
            <div class="panelbody quote">
                <slot></slot>
            </div>
        </div>
        
    </div>
</template>

<script>

export default {
   props: ['quotes'],
}
</script>

<style scoped>
    .panel-body {
        font-family: 'Arizonia', cursive;
        font-size: 24px;
        color: rgb(36, 32, 51);
    }
    .quote {
        cursor: pointer;
    }
    .quote:hover{
        background-color: #ffe2e2;
    }
</style>