<script>
    import Taskbar from '../components/Taskbar.svelte';
    import TaskbarIcon from '../components/Taskbar.svelte';
</script>

<style lang="postcss">
    :global(html) {
        background-image: url("../assets/background.jpg");
        background-repeat: no-repeat;
        background-size: cover;
    }
</style>

<Taskbar>
    <TaskbarIcon icon="/assets/logo_1080x.png" title="Application Title"/>
</Taskbar>