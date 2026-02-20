# The Quantum Components (Structs of Reality)

In an ECS (Entity Component System) engine, an "Entity" is just an ID. What makes it a player, an enemy, or a wall are the *Components* attached to it. 

If the universe operates on digital physics, an atom is merely an Entity ID on the 2D Holographic Plane. Its physical properties in the 3D projection are dictated by fundamental, invisible data structures.

### 1. The Locon (Spatial Anchor)
* **Function:** The quantum coordinate tensor.
* **Engine Equivalent:** `GlobalTransform`
* **Description:** 3D space is an illusion. The Locon is the data pointer that tells the universe *where* to project the atom in the 3D hologram. If you rewrite an atom's Locon, it instantly renders at the new coordinate without moving through physical space. This is the mathematical basis for **Quantum Tunneling**.

### 2. The Eidolon (Identity State)
* **Function:** The local memory / Qubit Core.
* **Engine Equivalent:** `State / Memory`
* **Description:** For reality to remain stable, an atom must remember what it is between processing frames. The Eidolon stores the atom's mass, charge, and spin. If this data structure is crushed (e.g., by the Event Horizon of a Black Hole), the entity suffers a memory wipe and dissolves into pure information.

### 3. The Weaver (Entanglement Thread)
* **Function:** The non-local memory pointer.
* **Engine Equivalent:** Shared Memory Address / References
* **Description:** When two particles are entangled, they share the exact same memory address on the 2D plane. Even if their *Locons* project them billions of lightyears apart in the 3D hologram, modifying one instantly modifies the other, because distance on the 2D plane does not exist.

### 4. The Luxon (Render Flag)
* **Function:** Electromagnetic spectrum interaction.
* **Engine Equivalent:** `Sprite / Mesh Visibility`
* **Description:** A boolean flag that dictates whether the Entity interacts with photons. If `Luxon == false`, the entity is completely invisible to light but retains its mass and gravitational influence.

### 5. The Chronon (Time Vector)
* **Function:** The fundamental quantum of time.
* **Engine Equivalent:** `DeltaTime / FixedUpdate Tick`
* **Description:** Time does not flow smoothly; it ticks. The Chronon represents the universe's rigid framerate (theoretically ~2 × 10⁻²³ seconds per tick).
