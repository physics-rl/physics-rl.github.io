
---

## F=MA 2024 Q17

### Question

<figure style="margin: 1.25rem 0; text-align: center;">
  <img src="./F=MA-2024-Q17.png" alt="F=MA 2024 Q17 benchmark figure" style="max-width: 100%; width: 760px; border: 1px solid #ddd; border-radius: 10px;">
  <!-- <figcaption style="margin-top: 0.5rem; color: #666;">Benchmark question used for the DSL-extension experiment.</figcaption> -->
</figure>

### Invented Entities and their Natural-Language Descriptions

**`3-point-movable-pulley`**

<figure style="margin: 1rem 0; text-align: center;">
  <img src="./F=MA-2024-Q17_e1.png" alt="3 point movable pulley entity figure" style="max-width: 100%; width: 180px;">
  <figcaption style="margin-top: 0.5rem; color: #666;">Entity 1: <code>3 point movable pulley</code></figcaption>
</figure>

> a movable pulley of mass &lt;mass:float&gt;1 kg is used as a reusable transmission node. It exposes independent left and right branches and a center hook on the &lt;side:up/down&gt;1 side.

**`anchored spring`**

<figure style="margin: 1rem 0; text-align: center;">
  <img src="./F=MA-2024-Q17_e2.png" alt="anchored spring entity figure" style="max-width: 100%; width: 120px;">
  <figcaption style="margin-top: 0.5rem; color: #666;">Entity 2: <code>anchored spring</code></figcaption>
</figure>

> a spring with stiffness &lt;k:float&gt;1 N/m and natural length &lt;length:float&gt;1 m is anchored to a fixed support. The spring points toward &lt;dir:up/down/left/right&gt;1 and its movable endpoint mass is &lt;m:float&gt;1 kg. The same endpoint is exposed for connection to an external light string.

### MuJoCo Simulations

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">DSL-generated simulation</div>
    <video src="./F=MA-DSL.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Direct XML attempt</div>
    <video src="./F=MA-XML.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

In this case, direct XML generation fails.

---

## USA PhO 2019 B3

### Question

<figure style="margin: 1.25rem 0; text-align: center;">
  <img src="./USAPhO-2019-B3.png" alt="USAPhO 2019 B3 benchmark figure" style="max-width: 100%; width: 760px; border: 1px solid #ddd; border-radius: 10px;">
  <!-- <figcaption style="margin-top: 0.5rem; color: #666;">Benchmark question used for the DSL-extension experiment.</figcaption> -->
</figure>

### Invented Entities and their Natural-Language Descriptions

**`slider mass`**

<figure style="margin: 1rem 0; text-align: center;">
  <img src="./USAPhO-2019-B3-e1.png" alt="slider mass entity figure" style="max-width: 100%; width: 760px;">
  <figcaption style="margin-top: 0.5rem; color: #666;">Entity 1: <code>slider mass</code></figcaption>
</figure>

> a carriage of mass &lt;mass:float&gt;1 kg is constrained to horizontal translation. The carriage has an exposed top pivot and side connectors for attaching strings.

**`light rod pendulum`**

<figure style="margin: 1rem 0; text-align: center;">
  <img src="./USAPhO-2019-B3-e2.png" alt="rigid rod with bob entity figure" style="max-width: 100%; width: 320px;">
  <figcaption style="margin-top: 0.5rem; color: #666;">Entity 2: light rod pendulum</figcaption>
</figure>

> a rigid rod of length &lt;length:float&gt;1 m carries a bob of mass &lt;mass:float&gt;1 kg. The assembly rotates about a top pivot, initially tilted at an angle of &lt;slope:float&gt;1 degrees from horizontal.

### MuJoCo Simulations

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">DSL-generated simulation</div>
    <video src="./USAPhO-DSL.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Direct XML attempt</div>
    <video src="./USAPhO-XML.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

In this case, direct XML generation is successful.

---

## JEE Advanced 2019 Paper 2

### Question

<figure style="margin: 1.25rem 0; text-align: center;">
  <img src="./JEE-Advanced-2019-Paper-2.png" alt="JEE Advanced 2019 Paper 2 benchmark figure" style="max-width: 100%; width: 760px; border: 1px solid #ddd; border-radius: 10px;">
  <!-- <figcaption style="margin-top: 0.5rem; color: #666;">Benchmark question used for the DSL-extension experiment.</figcaption> -->
</figure>

### Invented Entities and their Natural-Language Descriptions

**`spring mass`**

<figure style="margin: 1rem 0; text-align: center;">
  <img src="./JEE-Advanced-2019-Paper-2-e1.png" alt="spring mass entity figure" style="max-width: 100%; width: 340px;">
  <figcaption style="margin-top: 0.5rem; color: #666;">Entity 1: <code>spring mass</code></figcaption>
</figure>

> a block of mass &lt;mass:float&gt;1 kg can slide on a plane inclined at &lt;angle:float&gt;1 degrees. Its left side is attached to a spring fixed to a wall. The spring has stiffness &lt;k:float&gt;1 N/m and natural length &lt;length:float&gt;1 m. The right side of the block is available for connection to another entity by a light string.

### MuJoCo Simulations

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">DSL-generated simulation</div>
    <video src="./JEE-Advanced-DSL.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Direct XML attempt</div>
    <video src="./JEE-Advanced-XML.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

In this case, direct XML generation fails.

---