# PHYS-Lab-Config

Public configuration files for CU Boulder Physics lab software.

## Structure

```
phys2150/defaults.json   # PHYS 2150 Measurement Suite configuration
```

## Usage

Lab applications fetch their configuration at startup from this repository using the raw GitHub URL:

```
https://raw.githubusercontent.com/UCBoulder/PHYS-Lab-Config/main/<course>/defaults.json
```

This allows configuration updates to be deployed without rebuilding or reinstalling lab software.
