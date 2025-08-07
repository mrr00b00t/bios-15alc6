# Lenovo IdeaPad 15ALC6 - BIOS Update History  BIOS 💻

This repository contains a collection of historical BIOS update files for the **Lenovo IdeaPad 15ALC6** laptop.


## Why does this exist?

This archive was created after observing a significant regression with a recent BIOS update. The update version **`GLCN68WW`** (and potentially subsequent versions) appears to **disable support for the AMD P-State driver (`amd_pstate`) in Linux**.

AMD P-State is a modern and efficient CPU frequency scaling driver that can offer superior performance and power management on supported AMD Ryzen processors. Its removal forces the system to fall back to the older `acpi-cpufreq` driver, which may result in less optimal performance and battery life.

By maintaining a history of previous BIOS versions, users who experience this or other issues have the option to **roll back** their firmware to a version that works best for their needs.


## Files Included

*  13M 2021-04-25 05:50 glcn23ww.exe
* 3,1K 2021-04-25 05:49 glcn23ww.txt
*  13M 2021-05-12 23:27 glcn24ww.exe
* 3,0K 2021-05-12 23:27 glcn24ww.txt
*  13M 2021-04-27 03:53 glcn34ww.exe
* 2,9K 2021-04-27 04:15 glcn34ww.txt
*  13M 2021-05-27 09:10 glcn36ww.exe
* 2,9K 2021-05-27 09:11 glcn36ww.txt
*  13M 2021-08-02 04:16 glcn39ww.exe
* 3,2K 2021-08-02 04:16 glcn39ww.txt
*  13M 2021-10-09 02:37 glcn40ww.exe
* 3,2K 2021-10-09 02:37 glcn40ww.txt
*  13M 2021-09-14 03:00 glcn41ww.exe
* 3,4K 2021-12-12 23:56 glcn41ww.txt
*  13M 2021-12-20 04:55 glcn42ww.exe
* 3,4K 2022-01-07 04:37 glcn42ww.txt
*  13M 2022-01-07 02:40 glcn43ww.exe
* 3,2K 2022-01-26 05:22 glcn43ww.txt
*  13M 2022-02-16 23:00 glcn44ww.exe
* 3,5K 2022-03-02 23:13 glcn44ww.txt
*  21M 2022-04-06 04:55 glcn46ww.exe
* 3,2K 2022-04-07 02:48 glcn46ww.txt
*  21M 2022-05-13 03:10 glcn48ww.exe
*  24K 2022-05-13 03:10 glcn48ww.txt
*  21M 2022-07-05 06:45 glcn50ww.exe
* 3,3K 2022-09-05 03:40 glcn50ww.txt
*  21M 2022-09-28 06:45 glcn51ww.exe
* 3,2K 2022-10-18 05:09 glcn51ww.txt
*  21M 2022-12-09 07:45 glcn52ww.exe
* 3,2K 2023-02-14 05:19 glcn52ww.txt
*  21M 2024-02-06 03:54 glcn55ww.exe
*  27K 2024-02-06 03:53 glcn55ww.txt
*  21M 2024-03-27 06:06 glcn57ww.exe
*  27K 2024-03-27 06:06 glcn57ww.txt
*  21M 2024-08-08 00:46 glcn63ww.exe
*  29K 2024-08-08 00:46 glcn63ww.txt
*  21M 2025-02-19 03:21 glcn66ww.exe
*  31K 2025-02-19 03:22 glcn66ww.txt
*  14M 2025-06-19 00:37 glcn68ww.exe
*  36K 2025-05-27 03:24 glcn68ww.txt

For each BIOS version `glcnXXww`, you will find two files:

* **`glcnXXww.exe`**: The executable BIOS flashing utility. This program must be run from a Windows environment to update or downgrade your BIOS.
* **`glcnXXww.txt`**: The official release notes (changelog) for the corresponding BIOS version. It is highly recommended to read this file before flashing.


## IMPORTANT WARNING: Proceed with Caution!

Flashing your computer's BIOS is a sensitive operation. Downgrading (or "back flashing") can be especially risky if not done correctly.

* **RISK OF BRICKING**: An incorrect or failed BIOS flash can render your computer permanently unusable (a "brick"). Proceed **at your own risk**.
* **BACK UP YOUR DATA**: Always back up all important data before attempting a BIOS update or downgrade.
* **ENABLE BIOS BACK FLASH**: To downgrade your BIOS, you will likely need to enter your current BIOS setup (by pressing F2, Del, or another key during boot) and find an option like "**BIOS Back Flash**" or "**Allow BIOS Downgrade**" and **enable it**.
* **POWER SOURCE**: Ensure your laptop is connected to a reliable power source and fully charged before beginning the process. A power loss during the flash will corrupt the BIOS.

These files are provided as-is, with no warranty of any kind. This archive is for preservation and troubleshooting purposes for advanced users.
