<script>
    import Taskbar from '../components/Taskbar.svelte';
    import TaskbarIcon from '../components/TaskbarIcon.svelte';
    import DesktopIcon from '../components/Taskbar.svelte';
</script>

<style lang="postcss">
    :global(html) {
        background-image: url("../assets/background.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        margin: 0;
    }
</style>

<!--Desktop icons-->
<div class="h-screen w-full m-0">
    <DesktopIcon icon="/assets/logo_1080x.png" title="Application Title"/>
</div>

<Taskbar>
    <TaskbarIcon icon="/assets/logo_1080x.png" title="Application Title"/>
</Taskbar>