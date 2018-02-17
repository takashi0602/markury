<template lang="pug">
    .container
        textarea.markdown
        .result
            h1 hoge
</template>

<script>
    export default {
        data() {
            return {
                input: '# hello, markury!'
            }
        },

    }
</script>

<style lang="scss">
    html, body, #app {
        width: 100%;
        height: 100%;
        margin: 0;
        padding: 0;
    }
    .container {
        width: 100%;
        height: 100%;
        margin: 0;
        padding: 0;
        overflow: hidden;
    }
    .markdown {
        display: inline-block;
        width: 50%;
        height: 100%;
        vertical-align: top;
        box-sizing: border-box;
        padding: 20px;
        border: none;
        border-right: 1px solid #ccc;
        resize: none;
        outline: none;
        background-color: #f6f6f6;
        font-size: 14px;
        font-family: 'Monaco', courier, monospace;
    }
    .result {
        display: inline-block;
        width: 50%;
        height: 100%;
        vertical-align: top;
        box-sizing: border-box;
        padding: 0 20px;
        font-family: 'Helvetica Neue', Arial, sans-serif;
        color: #333;
    }
</style>