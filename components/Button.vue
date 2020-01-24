<template>
  <a
    :style="{ margin: margin }"
    target="__blank"
    href="https://pay.hotmart.com/G20235081F"
    class="StyledBtn">
    <slot />
  </a>
</template>

<script>
export default {
  name: 'StyledButton',
  props: {
    margin: { type: String, default: '0px' },
  },
};
</script>

<style lang="scss" scoped>
.StyledBtn {
  position: relative;
  border: 1px solid #06ef07;
  background-color: transparent;
  padding: 20px 30px;
  font-size: 20px;
  font-weight: 600;
  border-radius: 500px;
  width: 270px;
  text-transform: uppercase;
  text-align: center;
  outline: none;
  color: #06ef07;
  transition: all 0.1s ease-in;

  &:hover {
    background-color: #06ef07;
    color: #fff;
    cursor: pointer;
  }

  &::after {
    position: absolute;
    content: 'treinamento 100% online';
    font-size: 10px;
    color: #ccc;
    font-weight: 700;
    top: -20px;
    left: 42px;
  }
}
</style>
