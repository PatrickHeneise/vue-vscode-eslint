<template>
  <div class="hello">
    <div class="field is-horizontal">
      <div class="field-label is-normal">
        <label class="label">Current Home</label>
      </div>
      <div class="field-body">
        <div class="field">
          <p class="control">
            <input
              required
              class="input is-static"
              type="text"
              value="hello"
              readonly
            />
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss"></style>
