# Unbrick Redmi 9T - Hard Brick Solution

This repository provides a step-by-step guide to recover a hard-bricked Redmi 9T using **Prime Mi Flash Tool**.

## Steps

1. **Download and install** Prime Mi Flash Tool (modded version for Redmi 9T).  
2. **Download the correct stock ROM** for your device (Redmi 9T, global/India version).  
3. **Replace the firehose loader** in the ROM’s `images` folder:
   - Use a patched `prog_firehose_ddr.elf`
   - Keep the exact filename  
4. **Connect the device in EDL mode** (it should appear as QDLoader 9008).  
5. **Flash the ROM**:
   - Launch Prime Mi Flash Tool as Administrator
   - Select the ROM folder
   - Confirm the device
   - Start the flash process  
6. **Charge your device** after recovery, especially if the battery was low.  

## Tips

- Use a **quality USB cable** and connect directly to the PC (avoid hubs).  
- Always keep the **firehose loader filename intact**.  
- Ensure the device is **charged immediately after flashing**.  
- Prime Mi Flash Tool is reliable for recovering hard-bricked Redmi 9T devices.
