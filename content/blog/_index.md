---
title: "Blog & Wawasan"
description: "Artikel terbaru seputar teknologi."
---

{{< ui-v1/container class="mx-auto" >}}
    {{< ui-v1/container class="py-20" >}}

        {{< ui-v1/stack align="center" gap="4" class="mb-12 text-center" >}}
            <h1 class="h1">Jelajahi Tulisan Kami</h1>
            <p class="body-1 text-neutral-500 max-w-2xl">
                Tutorial, tips, dan trik seputar Next.js, Hugo, dan Web Development.
            </p>
        {{< /ui-v1/stack >}}

        {{< ui-v1/box class="mb-10" >}}
            {{< ui-v1/dropdown label="Filter Kategori" hover="true" >}}
                {{< ui-v1/dropdown-item name="Semua" url="/blog" >}}
                {{< ui-v1/dropdown-item name="Coding" url="/tags/coding" >}}
                {{< ui-v1/dropdown-item name="Design" url="/tags/design" >}}
            {{< /ui-v1/dropdown >}}
        {{< /ui-v1/box >}}

    {{< /ui-v1/container >}}

    {{< ui-v1/container class="py-20 border-t border-neutral-200" >}}
        {{< ui-v1/box class="bg-transparent p-12 rounded-3xl text-center" >}}
            <h2 class="h2 mb-4">Belum puas membaca?</h2>
            {{< ui/button variant="barinwave" url="/archive" >}}
                Lihat Arsip Lengkap
            {{< /ui/button >}}
        {{< /ui-v1/box >}}
    {{< /ui-v1/container >}}

    {{< ui/button size="sm" >}} Small {{< /ui/button >}}
    {{< ui/button size="lg" >}} Large Call to Action {{< /ui/button >}}

    {{< ui/button variant="default" href="/login" >}} Sign In {{< /ui/button >}}

    {{< ui/button variant="secondary" >}} Download {{< /ui/button >}}

    {{< ui/button variant="outline" href="/docs" >}} Read Docs {{< /ui/button >}}

    {{< ui/button variant="ghost" >}} Cancel {{< /ui/button >}}

    {{< ui/button variant="destructive" >}} Delete Account {{< /ui/button >}}



    {{< ui-v1/card class="w-full max-w-sm mx-auto" >}}

        {{< ui-v1/card/card-header >}}
            <div>
                {{< ui-v1/card/card-title >}}Login to your account{{< /ui-v1/card/card-title >}}
                {{< ui-v1/card/card-description >}}Enter your email below to login{{< /ui-v1/card/card-description >}}
            </div>
            
            {{< ui-v1/card/card-action >}}
                {{< ui/button variant="link" href="/signup" >}}Sign Up{{< /ui/button >}}
            {{< /ui-v1/card/card-action >}}
        {{< /ui-v1/card/card-header >}}


        {{< ui-v1/card/card-footer class="flex-col gap-2" >}}
            {{< ui/button type="submit" class="w-full" >}}
                Login
            {{< /ui/button >}}
            
            {{< ui/button variant="outline" class="w-full" >}}
                Login with Google
            {{< /ui/button >}}
        {{< /ui-v1/card/card-footer >}}

    {{< /ui-v1/card >}}

    {{< ui/separator >}}


    {{< ui/separator decorative="true" class="my-2 bg-secondary-400" >}}


    {{< ui/input type="email" placeholder="Email Address" >}}
    
{{< /ui-v1/container >}}


{{< ui-v1/container class="mx-auto" >}}
    
    <h2 class="text-3xl font-bold mb-10 text-center">Our Features</h2>

    {{< ui-v1/grid cols="3" gap="8" >}}
        
        {{< ui-v1/box class="p-6 bg-netral-50 rounded-xl border border-netral-200" >}}
            <h3 class="font-bold mb-2">⚡ Super Cepat</h3>
            <p>Dibangun di atas Hugo yang sangat ringan.</p>
        {{< /ui-v1/box >}}

        {{< ui-v1/box class="p-6 bg-netral-50 rounded-xl border border-netral-200" >}}
            <h3 class="font-bold mb-2">🎨 Tailwind v4</h3>
            <p>Styling modern tanpa config yang ribet.</p>
        {{< /ui-v1/box >}}

        {{< ui-v1/box class="p-6 bg-netral-50 rounded-xl border border-netral-200" >}}
            <h3 class="font-bold mb-2">🧠 Smart Components</h3>
            <p>Logika Alpine.js yang reaktif.</p>
        {{< /ui-v1/box >}}

    {{< /ui-v1/grid >}}

{{< /ui-v1/container >}}

{{< ui-v1/container class="mx-auto" >}}
    {{< ui/button variant="barinwave" url="/archive">}}
            Lihat Arsip Lengkap
    {{< /ui/button >}}
    {{< ui/button variant="barinwave" url="/archive">}}
            Welcome
    {{< /ui/button >}}
    {{< ui/button variant="primary" url="/archive">}}
            Welcome
    {{< /ui/button >}}
{{< /ui-v1/container >}}


