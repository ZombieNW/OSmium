<script>

</script>

<div class="absolute bottom-0 h-12 w-full taskbar rounded-tl-2xl rounded-tr-2xl hover:h-[4rem] transition-all flex items-center">
    <slot>
        <h1>fallback</h1>
    </slot>
</div>

<style>
    .taskbar{
        background: rgb(32,32,40);
        background: linear-gradient(180deg, rgba(32,32,40,1) 0%, rgba(25,25,32,1) 100%);
    }
</style>