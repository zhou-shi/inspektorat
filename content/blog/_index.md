---
title: "Blog & Wawasan"
description: "Artikel terbaru seputar teknologi."
---

{{< ui/container class="mx-auto" >}}
    {{< ui/container class="py-20" >}}

        {{< ui/stack align="center" gap="4" class="mb-12 text-center" >}}
            <h1 class="h1">Jelajahi Tulisan Kami</h1>
            <p class="body-1 text-neutral-500 max-w-2xl">
                Tutorial, tips, dan trik seputar Next.js, Hugo, dan Web Development.
            </p>
        {{< /ui/stack >}}

        {{< ui/box class="mb-10" >}}
            {{< ui/dropdown label="Filter Kategori" hover="true" >}}
                {{< ui/dropdown-item name="Semua" url="/blog" >}}
                {{< ui/dropdown-item name="Coding" url="/tags/coding" >}}
                {{< ui/dropdown-item name="Design" url="/tags/design" >}}
            {{< /ui/dropdown >}}
        {{< /ui/box >}}

    {{< /ui/container >}}

    {{< ui/container class="py-20 border-t border-neutral-200" >}}
        {{< ui/box class="bg-neutral text-white p-12 rounded-3xl text-center" >}}
            <h2 class="h2 mb-4">Belum puas membaca?</h2>
            {{< ui/button variant="primary" url="/archive" >}}
                Lihat Arsip Lengkap
            {{< /ui/button >}}
        {{< /ui/box >}}
    {{< /ui/container >}}

    {{< ui/button size="sm" >}} Small {{< /ui/button >}}
    {{< ui/button size="lg" >}} Large Call to Action {{< /ui/button >}}

    {{< ui/button variant="default" href="/login" >}} Sign In {{< /ui/button >}}

{{< ui/button variant="secondary" >}} Download {{< /ui/button >}}

{{< ui/button variant="outline" href="/docs" >}} Read Docs {{< /ui/button >}}

{{< ui/button variant="ghost" >}} Cancel {{< /ui/button >}}

{{< ui/button variant="destructive" >}} Delete Account {{< /ui/button >}}


{{< /ui/container >}}

