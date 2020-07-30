---
created_at: '2011-09-19T14:29:47Z'
id: Spoilermärkning
links:
  category:
  - Mallar
title: Spoilermärkning
---

Så här gör man en spoiler:

    '''Spoiler:'''<span style="color:#fff;"> Det här är en spoiler. </span> 

Som ser ut så här:

**Spoiler:**<span style="color:#fff;"> Det här är en spoiler. </span>

Taggarna ändrar alltså textfärgen till samma som bakgrundsfärgen.

Om man börjar raden med ett mellanslag får man dessutom en sån här box:

**Spoiler:**<span style="color:#fff;"> Det här är en spoiler. </span>

Notera att sådana boxar inte har automatisk radbrytning (och en del andra egenheter).

Man kan också göra en box såhär:

     <blockquote style="background: #eee;">Text i en box </blockquote> 

Som då ser ut såhär:

> Text i en box

En spoiler i en sån box ska göras såhär:

     <blockquote style="background: #eee;">'''Spoiler:'''<span style="color:#eee;"> Det här är en spoiler. </span> </blockquote> 

Och se ut såhär:

> **Spoiler:**<span style="color:#eee;"> Det här är en spoiler. </span>

Man kan också göra den här varianten:

    '''Spoiler:'''<span style="background: #eee;"> <span style="color:#eee;"> Det här är en spoiler. </span> </span> 

Som ser ut såhär:

**Spoiler:**<span style="background: #eee;"> <span style="color:#eee;"> Det här är en spoiler.
</span> </span>