<template>
  <Card>
    <div>
      <div>
        <span>ระยะค้นหา</span>
        <span style="float: right; padding: 3px 0">{{this.value2}} เมตร</span>
      </div>
      <Slider v-model="value2" :step="300" max="1200" :showTooltip="false" show-stops></Slider>

      <Button @click="search" style="width:100%" type="success">ค้นหาร้านอาหาร</Button>
    </div>
  </Card>
</template>

<script>
import { Card, Slider, Button, Row } from 'element-ui'

export default {
  components: {
    Card,
    Slider,
    Button,
    Row
  },
  data() {
    return {
      value2: 100
    }
  }
}
</script>
