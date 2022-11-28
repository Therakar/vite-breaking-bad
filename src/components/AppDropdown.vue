<script>
    export default{
  name: "AppDropdown"
}
</script>

<template>
    <div class="container dropdown">
        <select name="" id="">
            <option selected>Select category</option>
            <option value="1">Name</option>
            <option value="2">Status</option>
        </select>
    </div>
</template>



<style lang="scss" scoped>
    .dropdown{
        width: 87.5rem;
        margin-top: 30px;
        margin-bottom: 20px;

        select{
            padding: 9px;
            border-radius: 5px;
            color: var(--primary-color);
        }
        
    }
        
</style>