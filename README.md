# RCWS Mechanism Repo

This repository contains the original SolidWorks design files for the RCWS mechanism.

## Software Requirements

- SolidWorks ≥ 2023

## Folder Description

- `assembly`: shows how the main board is assembled with the top and bottom covers
- `part`: contains the `.sldprt` or `.step` files for the top cover, bottom cover, and ring
- `pcb`: contains the `.sldprt` file(s) related to the main board
- `stl`: contains the STL files used; all components are manufactured via 3D printing using these STL files

## Trouble Shooting

> File missing error when opening the assembly file?

- When opening `assembly/main_assem.sldasm` for the first time, adjust the external reference paths as follows:
  - `DRV_STM_main_2spi_pcb.sldprt` ➞ `pcb/DRV_STM_main_2spi_pcb.sldprt`
  - `DRV_STM_closure_bottom.sldprt` ➞ `part/DRV_STM_closure_bottom.sldprt`
