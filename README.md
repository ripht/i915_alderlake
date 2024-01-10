# i915_alderlake
>6.7 kernel patch for poor VBT factory bios firmwares.
>
>For a while some machines like the new gen HP Spectre x360's and some lenovo's ship with a wrong bios VBT. This patch skips an init line in the i915 driver so the Port B never gets processed from the VBT.
>intel_display.c seems to be overhauled with some regularity, so this patch manipulates intel_bios.c in stead. 
