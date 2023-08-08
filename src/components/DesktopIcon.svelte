<script>
    export let title = "Untitled";
    export let icon = "/assets/logo_1080x.png";

    if (title.length <= 32) {} else {
        title = title.slice(0, 32 - 3) + '...';
    }
</script>

<div class="flex m-8 w-24 rounded-xl flex-col">
    <img src="{icon}" alt="Logo" class="shadow-lg w-24">
    <h1 class="text-white text-xl" >{title}</h1>
</div>