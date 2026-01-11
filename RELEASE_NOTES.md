## 🧰 Asset Pack Stabilization (Atlas + Inventory Fixes) 🧱

### 🔄 Changed
- Rebuilt the cube‑net atlas from all registered block textures.
- Added the full block texture set used by the game inventory.
- Normalized the Door Open texture name to match runtime atlas indexing.
- Cleaned legacy/unneeded files from the asset pack.

### ✅ Fixes
- Inventory blocks no longer show broken/missing previews.
- Block faces wrap correctly in‑world and in‑hand.

### ⚙️ Technical Impact
- 🧱 Ensures full atlas coverage for all block IDs
- 📦 Keeps `Assets.zip` consistent with the in‑game registry
- 🧼 Removes stray files that caused inconsistencies

### 💡 Rationale
This release aligns the asset pack with the current BlockRegistry + cube‑net atlas layout
so every block renders consistently across inventory, hand, and world views.

---

🪄 *Crisp blocks. Correct atlas. Consistent inventory.* 🪄
