<script lang="ts">
    export let inputType:string ;
    export let label: string = '';
</script>

<input type="{inputType}" name="" id="{label}" placeholder="{label}">


<style>
    input{
        border: none;
        outline: none;
        padding: 20px;
        height: 40px;
        width: 100%;
        margin-bottom: 16px;
        border-radius: 12px;
    }
    input::-webkit-input-placeholder{
        font-weight: 400;
        font-size: 14px;
        color: #000;
        text-transform: capitalize;

    }
</style>