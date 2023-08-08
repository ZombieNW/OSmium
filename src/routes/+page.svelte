<script>
    import Window from '../components/Window.svelte';
    import Taskbar from '../components/Taskbar.svelte';
    import DesktopIcon from '../components/DesktopIcon.svelte';
</script>

<style lang="postcss">
    :global(html) {
        background-image: url("../assets/background.jpg");
        background-repeat: no-repeat;
        background-size: cover;
    }
</style>

<Taskbar>
</Taskbar>