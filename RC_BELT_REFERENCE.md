# RC Car Timing Belt Reference Guide

## Common RC Belt Specifications by Brand and Model

### 1/10 Scale Touring Cars

#### **Yokomo BD11**
- Belt: S3M 204 (204 teeth, 3mm pitch)
- Width: 6mm
- `belting("loop", "S3M", tooth_count = 204, belting_width = 6);`

#### **Xray T4 Series**
- Front Belt: S3M 171 (6mm wide)
- Rear Belt: S3M 189 (6mm wide)
- `belting("loop", "S3M", tooth_count = 171, belting_width = 6);`
- `belting("loop", "S3M", tooth_count = 189, belting_width = 6);`

#### **Team Associated TC7/TC7.1/TC7.2**
- Belt: S3M 180 (6mm wide)
- `belting("loop", "S3M", tooth_count = 180, belting_width = 6);`

#### **Tamiya TRF419/420**
- Front Belt: S3M 87 (3mm wide)
- Rear Belt: S3M 93 (3mm wide)
- `belting("loop", "S3M", tooth_count = 87, belting_width = 3);`
- `belting("loop", "S3M", tooth_count = 93, belting_width = 3);`

### 1/10 Scale Off-Road

#### **Team Associated B6.3/B6.4**
- Belt: S3M 72 (6mm wide)
- `belting("loop", "S3M", tooth_count = 72, belting_width = 6);`

#### **Yokomo YZ-2**
- Belt: S3M 78 (4.5mm wide)
- `belting("loop", "S3M", tooth_count = 78, belting_width = 4.5);`

### 1/8 Scale

#### **Mugen MBX8**
- Center Belt: HTD 5mm pitch, 108 teeth (15mm wide)
- `belting("loop", "HTD_5mm", tooth_count = 108, belting_width = 15);`

#### **HB Racing D8 Series**
- Belt: S5M 120 (15mm wide) - Note: S5M not in current generator
- Alternative: HTD 5mm pitch

### Drift Cars

#### **MST RMX 2.0**
- Belt: S3M 171 (6mm wide)
- `belting("loop", "S3M", tooth_count = 171, belting_width = 6);`

#### **Yokomo YD-2**
- Belt: S3M 189 (6mm wide) 
- `belting("loop", "S3M", tooth_count = 189, belting_width = 6);`

### Pan Cars

#### **CRC Gen-X 10**
- Belt: S3M 90 (9mm wide)
- `belting("loop", "S3M", tooth_count = 90, belting_width = 9);`

## Belt Pitch Reference
- **S3M**: 3mm pitch (most common in 1/10 scale)
- **HTD 3mm**: 3mm pitch (heavy duty variant)
- **HTD 5mm**: 5mm pitch (common in 1/8 scale)
- **S5M**: 5mm pitch (less common)

## Common Teeth Counts
- 60-90 teeth: Small pulleys, short wheelbase
- 90-120 teeth: Medium applications
- 150-210 teeth: Long belt runs, touring cars

## Width Standards
- 3mm: Micro/Mini scale
- 4.5mm: Some off-road applications  
- 6mm: Standard 1/10 touring
- 9mm: Heavy duty 1/10, pan cars
- 15mm: 1/8 scale

## Tips for Custom Applications
1. Measure center-to-center pulley distance
2. Calculate: teeth = (2 × center_distance + π × (pulley1_teeth + pulley2_teeth)) / pitch
3. Round to nearest whole number
4. Common safety margin: add 2-4 teeth for tension adjustment