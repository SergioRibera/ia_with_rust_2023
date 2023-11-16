---
theme: seriph
class: center
background: false
drawings:
  persist: false
transition: slide-left
title: Inicio
exportFilename: ia_with_rust
---
<h1><span class="title">Rust</span> para potenciar la <span class="title">Inteligencia Artificial</span></h1>
---
theme: seriph
layout: center
class: text-center
background: false
transition: slide-left
title: Inicio
---

<img class="max-w-150px mx-auto" src="/RustLangES.gif" />
<br/>

<div>
    <h1><span class="title text-6xl">Rust</span><span class="text-6xl"> en Español</span></h1>
</div>

---
layout: speakers
background: false
transition: slide-down
title: Presentando Expositores
colorSchema: 'light'
---

<div class="left">
    <h1><span class="title text-6xl">Sergio</span><br/><span class="text-6xl">Ribera</span></h1>
</div>

<div class="right">
  <ContainerCard list-class="justify-center ">
    <div class="flex gap-3 flex-col">
      <IconText text="bento.me/sergioribera">
        <carbon-earth-filled />
      </IconText>
      <IconText text="@SergioRibera">
        <carbon-logo-github />
      </IconText>
      <IconText text="/in/sergioribera">
        <carbon-logo-linkedin />
      </IconText>
    </div>
  </ContainerCard>
</div>
---
theme: seriph
layout: center
class: text-center
background: false
transition: slide-left
title: Titulo Presentacion
colorSchema: 'light'
---
<h1>
    <span class="text-6xl">Relevancia de la </span><span class="title text-6xl">IA</span>
</h1>
<span>Como tecnologia emergente</span>
---
theme: seriph
layout: random
class: text-center
background: false
transition: slide-left
title: IA's populares
colorSchema: 'light'
---
<img v-click class="max-w-150px rounded-xl" src="/chatgpt.png" />
<img v-click class="max-w-150px" src="/copilot.png" />
<img v-click class="max-w-150px" src="/llama.png" />
<img v-click class="max-w-150px" src="/dalle.png" />
<img v-click class="max-w-150px rounded-xl" src="/empresas/17.png" />
---
theme: seriph
class: text-center
background: false
transition: slide-up
title: Inversion en los ultimos años en IA
colorSchema: 'light'
---
<h1>
    <span class="title">Inversion </span><span>en los ultimos años</span>
</h1>

<div class="flex w-full h-full flex-row gap-8 items-center transition">
    <h1 v-click>
        <span class="title">93.5</span><span> B $</span>
    </h1>
    <h1 v-click>
        <span class="title text-6xl">121.5</span><span> B $</span>
    </h1>
    <h1 v-click>
        <span class="title text-8xl">158.0</span><span> B $</span>
    </h1>
</div>
---
theme: seriph
class: text-center
background: false
transition: slide-left
title: Retos de la IA
colorSchema: 'light'
---
<h1> <span class="title text-6xl">Retos </span><span class="text-6xl">en la IA</span> </h1>

<div class="slidev-random h-[60%]">
    <ContainerCard v-click list-class="flex-col justify-center">
        <img class="max-w-70px" src="/retos/money.png" />
        <span>Costos</span>
    </ContainerCard>
    <ContainerCard v-click list-class="flex-col justify-center">
        <img class="max-w-70px" src="/retos/time.png" />
        <span>Tiempo</span>
    </ContainerCard>
    <ContainerCard v-click list-class="flex-col justify-center">
        <img class="max-w-70px" src="/retos/fingerprint.png" />
        <span>Huella de Carbono</span>
    </ContainerCard>
    <ContainerCard v-click list-class="flex-col justify-center">
        <img class="max-w-70px ml-3" src="/retos/rendimiento.png" />
        <span>Rendimiento</span>
    </ContainerCard>
    <ContainerCard v-click list-class="flex-col justify-center">
        <img class="max-w-70px" src="/retos/portabilidad.png" />
        <span>Portabilidad</span>
    </ContainerCard>
</div>
---
theme: seriph
class: text-center
background: false
transition: slide-left
title: Como funciona la IA?
colorSchema: 'light'
---
<h1>
    <span class="text-6xl">¿Como funciona la </span>
    <span class="title text-6xl">IA</span>
    <span class="title text-6xl">?</span>
</h1>
<div class="slidev-random h-[80%]">
    <img v-click class="max-w-100px" src="/db.png" />
    <img v-click class="max-w-100px" src="/db_process.png" />
    <div v-click>
        <img class="max-w-50px" src="/db.png" />
        <img class="max-w-50px" src="/db.png" />
    </div>
    <img v-click class="max-w-100px" src="/neuronal_network.png" />
    <img v-click class="max-w-100px" src="/deploy.png" />
</div>
---
class: text-center
background: false
transition: slide-up
title: Funcionamiento de las librerias actuales
colorSchema: 'light'
---
<h1><span class="title text-6xl">Librerias</span><span class="text-6xl"> Actuales</span></h1>

<div v-click-hide="4" class="flex h-full justify-center items-center">
    <div class="w-full grid grid-cols-5">
        <div></div>
        <img v-click class="max-w-150px" src="/python.png" />
        <div></div>
        <arrow v-click x1="390" y1="320" x2="550" y2="320" color="#f97316" width="3" arrowSize="1" />
        <img v-click class="max-w-150px" src="/c.png" />
        <div></div>
    </div>
</div>

<div v-click="4" class="flex h-full justify-center items-center">
    <div class="w-[500px] grid grid-cols-2">
        <div class="bg-blue border-4 border-[#ffedd5] rounded-tl-2xl p-4">
            <img class="max-w-150px mx-auto" src="/python.png" />
        </div>
        <div class="bg-[#fdce9a] border-t-4 border-r-4 border-[#ffedd5] rounded-tr-2xl p-4"></div>
        <div class="bg-[#fdce9a] border-l-4 border-b-4 border-[#ffedd5] rounded-bl-2xl p-4"></div>
        <div class="bg-[#fdce9a] border-r-4 border-b-4 border-[#ffedd5] rounded-br-2xl p-4">
            <img class="max-w-150px mx-auto" src="/c.png" />
        </div>
    </div>
</div>
---
class: text-center
background: false
transition: slide-left
title: Problema de usar lenguajes inseguros
highlighter: shiki
lineNumbers: false

colorSchema: 'light'
---
<h1><span class="text-6xl">El</span><span class="title text-6xl"> Problema</span></h1>

<div class="flex flex-col justify-center">
```c {all|4|7|all}
#include <stdio.h>

int main() {
    int *ptr = NULL;

    // Intento de escribir en un puntero nulo
    *ptr = 5;

    return 0;
}
```
    <img v-click class="max-w-450px mx-auto" src="/main_c.png" />
</div>
---
class: text-center
background: false
transition: slide-left
title: Librerias de python
colorSchema: light
---

<h1>
    <span class="text-6xl">Librerias para </span>
    <span class="title text-6xl">IA</span>
</h1>

<div class="w-full flex flex-row justify-center gap-8 pt-8">
    <div>
        <h1 v-click>
            <span>Pandas</span>
        </h1>
        <img v-click class="max-w-[300px] rounded-xl" src="/pandas_py.png" />
    </div>
    <div>
        <h1 v-click>
            <span>NumPy</span>
        </h1>
        <img v-click class="max-w-[300px] rounded-xl" src="/numpy.png" />
    </div>
</div>
<div class="w-full flex flex-row justify-center gap-8 pt-4">
    <div>
        <h1 v-click>
            <span>PyTorch</span>
        </h1>
        <img v-click class="max-w-[300px] rounded-xl" src="/pytorch.png" />
    </div>
    <div>
        <h1 v-click>
            <span>TensorFlow</span>
        </h1>
        <img v-click class="max-w-[300px] rounded-xl" src="/tensorflow.png" />
    </div>
</div>

---
class: text-center
background: false
transition: slide-up
title: Solucion Sencilla

highlighter: shiki
lineNumbers: false

colorSchema: 'light'
---
<h1>
    <span class="text-6xl">¿Porque</span>
    <span class="title text-6xl"> Rust</span>
    <span class="text-6xl">?</span>
</h1>

<div v-click-hide="1" class="w-full h-full flex flex-col justify-center items-center">
    <ContainerCard>
    <ul class="list-disc text-start">
        <li>Multiparadigma
        </li><li>
        Herramientas modernas
        </li><li>
        Memory safe (null safety, sin fugas de memoria, etc)
        </li><li>
        Concurrente de nacimiento
        </li><li>
        Sin Garbage Collector
        </li><li>
        Abstracciones sin costo
        </li><li>
        Enfocado en el rendimiento
        </li><li>
        Compilador inteligente
        </li>
    </ul>
    </ContainerCard>
</div>
<div v-click="1" class="flex flex-col justify-center">
```rust {all|2|4|6|all}
fn main() {
    let n;

    n = 5;

    println!("Numero: {n}");
}
```
    <img v-click class="max-w-750px mx-auto" src="/rust_1.png" />
</div>
---
class: text-center
background: false
transition: slide-left
title: Librerias de Rust en python
colorSchema: light
---

<h1>
    <span class="text-5xl">Librerias para </span>
    <span class="title text-5xl">IA</span>
    <span class="text-5xl"> con </span>
    <span class="title text-5xl">Rust</span>
</h1>

<div class="w-full flex flex-row justify-center gap-8 pt-8">
    <div>
        <h1 v-click>
            <span>Polars</span>
        </h1>
        <img v-click class="max-w-[300px] rounded-xl" src="/polars.png" />
    </div>
    <div>
        <h1 v-click>
            <span>candle</span>
        </h1>
        <img v-click class="max-w-[300px] rounded-xl" src="/candle.png" />
    </div>
</div>

<div class="w-full flex flex-row justify-center gap-8 pt-4">
    <div>
        <h1 v-click>
            <span>burn</span>
        </h1>
        <img v-click class="max-w-[300px] rounded-xl" src="/burn.png" />
    </div>
    <div>
        <h1 v-click>
            <span>leaf</span>
        </h1>
        <img v-click class="max-w-[300px] rounded-xl" src="/leaf.png" />
    </div>
</div>


---
class: text-center
background: false
transition: slide-left
title: Librerias de Rust en python
colorSchema: light
---

<h1>
    <span class="text-5xl">Librerias para </span>
    <span class="title text-5xl">IA</span>
    <span class="text-5xl"> con </span>
    <span class="title text-5xl">Rust</span>
</h1>

<v-clicks>
<div v-click-hide="2" class="flex justify-center">
    <img class="rounded-xl max-w-700px" src="/polars_bench.png" />
</div>
</v-clicks>
<div v-click="2" class="w-full flex flex-row justify-center gap-8 pt-4">
    <div>
        <h1>
            <span>PyO3</span>
        </h1>
```rust {all|all|6-11|1-4|all}
#[pyfunction]
fn sum(a: i32, b: i32) -> i32 {
    a + b
}

#[pymodule]
fn math(_py: Python<'_>, m: &PyModule) -> PyResult<()> {
    m.add_function(wrap_pyfunction!(sum, m)?)?;

    Ok(())
}
```
    </div>
    <div v-click class="flex items-center">
```python
from math import sum

sum(5, 5)
```
    </div>
</div>


---
class: text-center
background: false
transition: slide-left
title: Se usa en AI
colorSchema: light
---

<h1>
    <span class="text-4xl">Pero, </span>
    <span class="text-4xl">¿Ya se usa en </span>
    <span class="title text-4xl">Inteligencia Artificial</span>
    <span class="text-4xl">?</span>
</h1>

<div class="mx-auto w-[80%] h-[80%] grid grid-cols-2 gap-3 items-center">
    <img v-click-hide="3" src="/xai_announcement.png" class="max-h-[300px]" />
    <img v-click-hide="4" src="/xai.png" class="max-h-[300px]" />
    <img v-click src="/CvsRUST.png" />
</div>

<!--
Parentesis de explicacion, el porque rust y no
-->
---
class: text-center
background: false
transition: view-transition | slide-left
title: Empresas que usan Rust
preload: false
src: ./pages/empresas.md
---
---
class: text-center
background: false
transition: slide-left
title: Empresas que usan Rust 2
src: ./pages/empresas_2.md
---
---
layout: center
background: false
transition: slide-down
title: Informacion de la comunidad

colorSchema: 'light'
---
<img class="max-w-150px mx-auto" src="/RustLangES.gif" />
<br/>

<div>
    <h1><span class="title text-6xl">Rust</span><span class="text-6xl"> en Español</span></h1>
</div>

---
layout: speakers
background: false
transition: slide-down
title: Redes de la comunidad

colorSchema: 'light'
---
<div class="left flex-col">
    <img class="max-w-75px ml-[20%]" src="/RustLangES.gif" />
    <h1><span class="title text-6xl">RustLang</span><span class="text-6xl">ES</span></h1>
</div>

<div class="right">
  <ContainerCard list-class="justify-center ">
    <div class="flex gap-3 flex-col">
      <IconText text="rustlanges.github.io">
        <carbon-earth-filled />
      </IconText>
      <IconText text="rustlanges.github.io/blog">
        <carbon-book />
      </IconText>
      <IconText text="@RustLangES">
        <carbon-logo-github />
      </IconText>
      <IconText text="discord.gg/4ng5HgmaMg">
        <svg xmlns="http://www.w3.org/2000/svg" width="1.2em" height="1.2em" viewBox="0 0 24 24"><path fill="currentColor" d="M19.27 5.33C17.94 4.71 16.5 4.26 15 4a.09.09 0 0 0-.07.03c-.18.33-.39.76-.53 1.09a16.09 16.09 0 0 0-4.8 0c-.14-.34-.35-.76-.54-1.09c-.01-.02-.04-.03-.07-.03c-1.5.26-2.93.71-4.27 1.33c-.01 0-.02.01-.03.02c-2.72 4.07-3.47 8.03-3.1 11.95c0 .02.01.04.03.05c1.8 1.32 3.53 2.12 5.24 2.65c.03.01.06 0 .07-.02c.4-.55.76-1.13 1.07-1.74c.02-.04 0-.08-.04-.09c-.57-.22-1.11-.48-1.64-.78c-.04-.02-.04-.08-.01-.11c.11-.08.22-.17.33-.25c.02-.02.05-.02.07-.01c3.44 1.57 7.15 1.57 10.55 0c.02-.01.05-.01.07.01c.11.09.22.17.33.26c.04.03.04.09-.01.11c-.52.31-1.07.56-1.64.78c-.04.01-.05.06-.04.09c.32.61.68 1.19 1.07 1.74c.03.01.06.02.09.01c1.72-.53 3.45-1.33 5.25-2.65c.02-.01.03-.03.03-.05c.44-4.53-.73-8.46-3.1-11.95c-.01-.01-.02-.02-.04-.02zM8.52 14.91c-1.03 0-1.89-.95-1.89-2.12s.84-2.12 1.89-2.12c1.06 0 1.9.96 1.89 2.12c0 1.17-.84 2.12-1.89 2.12zm6.97 0c-1.03 0-1.89-.95-1.89-2.12s.84-2.12 1.89-2.12c1.06 0 1.9.96 1.89 2.12c0 1.17-.83 2.12-1.89 2.12z"/></svg>
      </IconText>
      <IconText text="/company/rustlanges">
        <carbon-logo-linkedin />
      </IconText>
    </div>
  </ContainerCard>
</div>
---
theme: seriph
layout: two-cols
class: text-center
background: false
transition: slide-up
title: QR de la comunidad
---

<img class="mx-auto max-w-170px" src="/qr_page.png" />
<h1 class="mt-3 mb-8">Web</h1>
<img class="mx-auto max-w-170px" src="/qr_github.png" />
<h1 class="mt-3 mb-8">Github</h1>

::right::

<img class="mx-auto max-w-170px" src="/qr_blog.png" />
<h1 class="mt-3 mb-8">Blog</h1>
<img class="mx-auto max-w-170px" src="/qr_linkedin.png" />
<h1 class="mt-3 mb-8">Linkedin</h1>


---
theme: seriph
layout: center
class: text-center
background: false
transition: slide-left
title: Final
---

<img class="max-w-150px mx-auto" src="/RustLangES.gif" />
<br/>

<div>
    <h1><span class="title text-6xl">Rust</span><span class="text-6xl"> en Español</span></h1>
</div>
