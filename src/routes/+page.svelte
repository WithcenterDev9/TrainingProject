<script lang="ts">
    let message = $state(null);
</script>

<h1>Training Project</h1>

<container>
    <textarea id="message" bind:value={message}></textarea>
</container>

<h1>{message}</h1>
<h1>{message}</h1>

<style>
    #message {
        resize: none;
        border-radius: 20px;
        border-width: 5px;
        text-align: center;
    }
</style>