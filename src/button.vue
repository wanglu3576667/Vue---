<template>
    <button class="g-button">按钮</button>
</template>
<style lang="scss">
     .g-button{
            font-size:var(--font-size);
            height: var(--button-height);
            padding: 0px 1em;
            background:var(--button-bg);
            border: 1px solid var(--button-border-color);
            border-radius: 4px; 
            &:hover{
                border-color:var(--button-border-color-hover);
            }
            &:active{
                background-color: var(--button-border-bg-active)
            }
            &:focus{
                outline: none;
                border-color:var(--button-border-color-hover);
            }
     }
</style>
<script>
export default {

}
</script>


