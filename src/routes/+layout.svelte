<script>
    import "./app.css";
    let { children } = $props();
</script>

<div style="display: grid;  min-height: 100vh;">
    {@render children()}
</div>

<style>
    div {
        background: repeating-linear-gradient(
            45deg,
            white 40px,
            white 40px,
            gray 80px
        );
    }
</style>
