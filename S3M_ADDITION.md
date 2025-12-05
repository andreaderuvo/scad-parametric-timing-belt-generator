# S3M Belt Profile Addition

This fork adds support for S3M (3mm pitch) timing belts, commonly used in radio-controlled (RC) cars and other small mechanical applications.

## Why S3M?

S3M belts are widely used in the RC hobby for:
- Power transmission in 1/10 and 1/8 scale RC cars
- Precise timing applications
- Compact mechanical designs requiring 3mm pitch

## Added Features

- **S3M Profile**: Full support for S3M timing belt generation
- **Default Parameters**: 3mm pitch, 1.14mm backing thickness, 6mm default width
- **Tooth Geometry**: Accurate S3M tooth profile for proper meshing

## Usage Example

```scad
// Generate a 72-tooth S3M belt, 9mm wide
belting("loop", "S3M", tooth_count = 72, belting_width = 9);

// Generate a 90-tooth S3M belt, 6.5mm wide  
belting("loop", "S3M", tooth_count = 90, belting_width = 6.5);
```

## Technical Details

- Pitch: 3mm
- Standard widths: 6mm, 9mm, 15mm (customizable)
- Backing thickness: 1.14mm
- Compatible with standard S3M pulleys

This addition maintains compatibility with all existing belt profiles while extending functionality for RC enthusiasts and makers.