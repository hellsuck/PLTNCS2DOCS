# Offsets

The `offsets` table contains pre-defined memory offsets for Counter-Strike 2. These offsets are updated automatically by the engine.

---

## `offsets.client_dll`

This table contains offsets relevant to `client.dll` memory locations.

| Offset Name | Type | Description |
| ----------- | ---- | ----------- |
| `dwLocalPlayerPawn` | `uintptr_t` | Offset to the local player pawn pointer. |
| `dwViewAngles` | `uintptr_t` | Offset to the view angles pointer. |
| `dwEntityList` | `uintptr_t` | Offset to the entity list pointer. |
| `dwViewMatrix` | `uintptr_t` | Offset to the view matrix pointer. |

---

> [!NOTE]
> Additional offsets may be added by Plutonium regularly. Check the cheat console or relevant community forums for a full list of available offsets.
