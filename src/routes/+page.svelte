<script>
    import Taskbar from '../components/Taskbar.svelte';
    import TaskbarIcon from '../components/TaskbarIcon.svelte';
    import DesktopIcon from '../components/DesktopIcon.svelte';
</script>

<style lang="postcss">
    :global(html) {
        background-image: url("../assets/background.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        margin: 0;
        overflow-y: hidden;
    }
</style>

<!--Desktop icons-->
<div class="grid grid-cols-9 grid-rows-3 grid-flow-col overflow-hidden h-screen w-full m-0">
    <DesktopIcon icon="/assets/logo_1080x.png" title="title"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="such title dsjfbvjhsadbf jsdhgfjhasbdfhg asdfbsdf sdbfsnd fs dfjsbdfjs df dbasjhdbajsd asvda sdh aksbdj "/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="title"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="such title dsjfbvjhsadbf jsdhgfjhasbdfhg asdfbsdf sdbfsnd fs dfjsbdfjs df dbasjhdbajsd asvda sdh aksbdj "/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="title"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="such title dsjfbvjhsadbf jsdhgfjhasbdfhg asdfbsdf sdbfsnd fs dfjsbdfjs df dbasjhdbajsd asvda sdh aksbdj "/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="title"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="such title dsjfbvjhsadbf jsdhgfjhasbdfhg asdfbsdf sdbfsnd fs dfjsbdfjs df dbasjhdbajsd asvda sdh aksbdj "/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="title"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="such title dsjfbvjhsadbf jsdhgfjhasbdfhg asdfbsdf sdbfsnd fs dfjsbdfjs df dbasjhdbajsd asvda sdh aksbdj "/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
    <DesktopIcon icon="/assets/logo_1080x.png" title="caw"/>
</div>

<Taskbar>
    <TaskbarIcon icon="/assets/logo_1080x.png" title="Application Title"/>
</Taskbar>