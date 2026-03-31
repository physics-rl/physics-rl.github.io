
---

## Scene Videos

### Collision

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">MuJoCo</div>
    <video src="../static/videos/collision.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Omniverse</div>
    <video src="./collision.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

### Orbital

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">MuJoCo</div>
    <video src="../static/videos/orbital.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Omniverse</div>
    <video src="./orbital.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

### Projectile

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">MuJoCo</div>
    <video src="../static/videos/projectile.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Omniverse</div>
    <video src="./projectile.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

### Pulley

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">MuJoCo</div>
    <video src="../static/videos/pulley.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Omniverse</div>
    <video src="./pulley.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

### Rocket

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">MuJoCo</div>
    <video src="../static/videos/rocket.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Omniverse</div>
    <video src="./rocket.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

### Spring

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">MuJoCo</div>
    <video src="../static/videos/spring.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Omniverse</div>
    <video src="./spring.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div>

<!-- ### Rotation / Pendulum

The Omniverse export for this scene is stored as `pendulum.mp4`, corresponding to the MuJoCo `rotation.mp4` scene.

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1rem 0 2rem 0;">
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">MuJoCo</div>
    <video src="../static/videos/rotation.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
  <div style="flex: 1 1 420px;">
    <div style="font-weight: 600; margin-bottom: 0.5rem;">Omniverse</div>
    <video src="./pendulum.mp4" controls muted loop playsinline preload="metadata" style="width: 100%; border-radius: 12px; border: 1px solid #ddd; background: #000;"></video>
  </div>
</div> -->

---

## Takeaway

These examples illustrate that once a scene is expressed in our higher-level DSL, the same abstractions can be re-instantiated in a different simulator backend. This supports our claim in the rebuttal that extending or porting the pipeline is practical at the level of entities and connection semantics, without requiring manual authoring of raw simulator code for every new scene.
