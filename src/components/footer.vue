<template>
  <div class="contrary">
		<div class="container">
            <Mission>
                <template slot="mission">
                    <div>任务一</div>
                </template>
                <template slot="brief">
                    <div>简介</div>
                </template>
            </Mission>
            <Mission>
                <template slot="mission">
                    <div>任务二</div>
                </template>
                <template slot="brief">
                    <div>简介</div>
                </template>
            </Mission>
            <Mission>
                <template slot="mission">
                    <div>任务三</div>
                </template>
                <template slot="brief">
                    <div>简介</div>
                </template>
            </Mission>
            <Mission>
                <template slot="mission">
                    <div>任务四</div>
                </template>
                <template slot="brief">
                    <div>简介</div>
                </template>
            </Mission>
            <Mission>
                <template slot="mission">
                    <div>任务五</div>
                </template>
                <template slot="brief">
                    <div>简介</div>
                </template>
            </Mission>
		</div>
	</div>
</template>

<script>

import Mission from './mission.vue'
export default {
    name:'Footer',
    components:{Mission}
}
</script>

<style>

</style>