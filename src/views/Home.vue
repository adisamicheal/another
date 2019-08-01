<template>
  <div class="home">
	<Fees />
    <Performance />
    <Statistics />
    <Absent />
    <Absentdays />
  </div>
</template>

<script>
  import Fees from '@/components/Fees.vue'
  import Performance from '@/components/Performance.vue'
  import Statistics from '@/components/Statistics.vue'
  import Absent from '@/components/Absent.vue'
  import Absentdays from '@/components/Absentdays.vue'


export default {
    name: 'app',
    components: {
      Fees,
      Performance,
      Statistics,
      Absent,
      Absentdays
    }
  } 
</script>
