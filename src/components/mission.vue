<template>
    <div class="col-md-4 penc">
        <a href="">
            <i class="pencil"></i>
            <h3><slot name="mission"></slot></h3>
            <p><slot name="brief"></slot></p> 
        </a>
	</div>
</template>

<script>

export default {
    name:'Mission',
}
</script>

<style>

</style>