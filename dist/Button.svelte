<button class="btn" on:click>
    <slot />
</button>
<style>
.btn {
    border: 1px solid rgb(209, 213, 219);
    border-radius: 0.375rem;
    cursor: pointer;
    padding: 0.375rem 1rem;
    font-size: 100%;
    background-color: inherit;
    color: #212121;
}
.btn:hover {
    border-width: 1px;
    border-radius: 0.375rem;
    border-color: rgb(164, 164, 164);
    background-color: rgb(238 238 238);
}
</style>