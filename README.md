# Test Case: Pip with Conda environment.yml Only

## Package Manager
Pip (Conda-based project)

## Python Version Detection
- **Source**: environment.yml (PRIORITY #8 - lowest)
- **Expected Version**: 3.8.16
- **Note**: No higher priority files present

## Files Present
- requirements.txt - Dependencies only
- environment.yml - python=3.8.16 (SHOULD WIN - only version source)

## Test Purpose
Test lowest priority file (environment.yml) when all higher priority files are absent.
Common in Conda/Anaconda data science projects.
