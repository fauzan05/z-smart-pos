<script setup>
import { Head } from '@inertiajs/vue3';
import { Button } from '@/Components/ui/button';
import { Card, CardContent, CardHeader, CardTitle } from '@/Components/ui/card';
</script>

<template>
    <Head title="POS App" />
    
    <div class="h-screen w-full flex items-center justify-center bg-gray-100">
        <Card class="w-[350px]">
            <CardHeader>
                <CardTitle>POS System Ready</CardTitle>
            </CardHeader>
            <CardContent>
                <p class="mb-4 text-sm text-gray-500">
                    Laravel + Vue + Inertia + Pinia + Shadcn sudah aktif!
                </p>
                <Button class="w-full">Klik Saya (Shadcn Button)</Button>
            </CardContent>
        </Card>
    </div>
</template>