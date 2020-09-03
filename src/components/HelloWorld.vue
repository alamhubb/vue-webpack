<template>
  <div>
    <div class="qky1">{{ hello }}
      <div class="qky2"></div>
    </div>

    <img src="../static/bluead.png"/>

  </div>
</template>

<script lang="ts">
import {Vue, Component,} from 'vue-property-decorator'

@Component
export default class HelloWorldVue extends Vue {
  hello = 'hello boy'

  created(){
    const symbol5 = Symbol.for('42');
    const symbol6 = Symbol.for('42');
    const symbol3 = Symbol('foo');

    console.log(symbol5 )
    console.log(symbol5 == symbol6)
  }
}
</script>
