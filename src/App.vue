<template>
  <div>
    <Row>
      <search-box />
    </Row>
  </div>
</template>

<script>

import { Row } from 'element-ui'
import SearchBox from './components/SearchBox'

export default {
  name: 'app',
  components: {
    SearchBox,
    Row
  },
  methods:{
    search(){
      return{

      }
    }
  }
}
</script>