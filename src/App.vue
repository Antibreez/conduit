<template>
  <div>
    <mcv-topbar></mcv-topbar>
    <router-view />
  </div>
</template>

<script>
import McvTopbar from '@/components/TopBar'

export default {
  name: 'McvApp',
  components: {
    McvTopbar,
  },
}
</script>
