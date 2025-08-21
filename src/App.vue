<script setup lang="ts">
import { Button, Alert } from "heroui-vue";
</script>

<template>
    <div class="flex h-svh w-full justify-center items-center">
        <div class="flex flex-col gap-4">
            <Alert
                color="success"
                title="Hello, world!"
                description="Power by Vue and HeroUI Theme"
            ></Alert>
            <Button color="primary">Click me</Button>
        </div>
    </div>
</template>
