# Monitor ICC Profiles

A collection of ICC color profiles for my commonly used external monitors. This repository is designed to be used as a submodule within my dotfiles setup for consistent color management.

## Repository Structure

```
├── profiles/
│   └── acer-xb271hu-asnvpm0n50bd.icc
└── README.md
```

## Profile Naming Convention

Profiles are named using the following format:
```
manufacturer-model-serialnumber.icc
```

## Integration with Dotfiles

This repository is designed to be used as a git submodule:

```bash
# Add as submodule to your dotfiles
git submodule add https://github.com/yourusername/monitor-icc-profiles.git config/icc-profiles

# Initialize after cloning dotfiles
git submodule update --init --recursive
```

## Monitor Information

| Manufacturer | Model | Serial | Profile | Calibrated |
|--------------|-------|--------|---------|------------|
| Acer Technologies | XB271HU | ASNVPM0n50bd | `acer-xb271hu-asnvpm0n50bd.icc` | 2025-06-04 02:24 |

## Calibration Settings

- White point: D65 (6500K)
- Target gamma: 2.2
- Calibration tool: Display Plus HL (Calibrite)
- Calibrated: 2025-06-04 02:24

## License

These ICC profiles are provided as-is for personal use. Profiles are specific to individual monitor units and may not be suitable for other displays of the same model.
