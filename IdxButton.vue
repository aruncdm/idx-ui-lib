<template>

    <v-btn
    v-bind="$attrs"
    :value="value"
      color="primary"
    > {{title}}
    </v-btn>

</template>

<script>
export default {
    inheritAttrs: false,
    props: ['title']
}
</script>