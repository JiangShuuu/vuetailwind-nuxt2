<template>
  <div>
    <client-only>
      <ModalT />
    </client-only>
    <div class="border" @click="$modal.show('donate-modal')">test</div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
