<template>
  <div>
    <header class="list-header">
      <slot name="header">Este es el header</slot>
    </header>
    <ul class="lista-mensajes">
      <slot></slot>
    </ul>
  </div>
</template>

<script>
export default {
  name: "MessageList"
};
</script>
