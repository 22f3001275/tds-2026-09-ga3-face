# TDS 2026 Sep GA3 — Q6 3D face

`face.glb`: a textured 3D bust of Jodie Whittaker made from one Wikimedia Commons photo
(`Jodie_Whittaker_GC_Columbus_2025_(cropped).jpg`).

- Shape: Hunyuan3D-2 (DiT v2-0), seed 7, octree 384, on the photo with the mic and hand inpainted out (SDXL).
- Texture: Hunyuan3D-Paint multiview with the real photo baked onto the front (silhouette-IoU + ECC alignment),
  side and back hair colour matched to the photo, 2048² JPEG.
- 1,683,324 bytes, glTF 2.0 binary, 0 errors / 0 warnings in the Khronos glTF validator.
- FaceNet identity vs. the photo, averaged over 0°, ±20°, ±35°, ±50°: 0.783.

`face_v*.glb` are earlier iterations, kept for comparison.
