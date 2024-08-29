# Exynos 7420 patches for cherishOS 20.0
You must apply all of the patches in this repository in order for proper building and booting. 

Only validated to work on cherishOS 20.0 (as of Jan 2024)

Extract files to ~/7420_patches-cherish-20.0. Copy apply.sh to the root of your cherish 20 sources.

Mark apply.sh as executable

```
sudo chmod +x apply.sh
```

Then run the apply.sh script. It should apply all of the patches you need

These patches are required because we are on an old kernel version. Certain things need to be bypassed in order to get it booting at all