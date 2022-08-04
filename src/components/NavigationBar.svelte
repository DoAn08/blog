<script lang="ts">

</script>
<style lang="scss">
    .navigationWrapper {
        display: flex;
        height: 64px;
        flex-direction: row;
        align-items: center;
    }
    .n_title {
        font-size: x-large;
        font-weight: 500;
        margin-left: 16px;
    }
    .n_nav {
        height: 24px;
        font-size: x-large;
        margin: 0 4px 0 auto;
    }
    .a_margin {
        margin: 0 16px 0 16px;
    }
    .n_action {
        transition: all 0.25s ease-in-out;
    }
    .n_action:hover {
        color: #4A4A4A;
    }
</style>
<div class="navigationWrapper">
    <div class="n_title">
        <p>DoAn08</p>
    </div>
    <div class="n_nav">
        <a href="#!" class="material-symbols-rounded a_margin n_action">home</a>
        <a href="#!" class="material-symbols-rounded a_margin n_action">help</a>
    </div>
</div>