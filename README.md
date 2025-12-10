# MRZ Check Digit Calculator

A web-based tool to calculate and validate MRZ (Machine Readable Zone) check digits according to ICAO 9303 standard.

## Features
- Calculate check digits for MRZ fields
- Validate existing check digits
- Support for all MRZ document types (TD1, TD2, TD3)

## How to Use
1. Enter your MRZ field (e.g., passport number, date)
2. Click "Calculate" to get the check digit
3. Or enter both field and check digit to validate
4. Use the examples for quick testing

## Technical Details
- Based on ICAO 9303 standard (ISO/IEC 7812-1)
- Uses weights: 7, 3, 1 repeated
- Character mapping: 0-9=0-9, A-Z=10-35, '<'=0

## Live Demo
Visit: [https://ihsanulrahman.github.io/check-digit](https://ihsanulrahman.github.io/check-digit)

