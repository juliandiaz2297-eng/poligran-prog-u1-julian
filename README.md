# poligran-prog-u1-julian
# Java Helpers for Module Project – Julian

All code, identifiers, and comments are in **English** (as required).  
This repo provides:
- `TilesCalculator`: minimal number of X-by-X tiles to cover an N-by-M area (no loops/ifs/Math).
- `DoubleUtils.equalsWithTolerance`: real-number equality check with tolerance.

## How to compile & run (JDK)
```bash
javac -d out src/com/julian/utils/TilesCalculator.java src/com/julian/demos/TilesDemo.java
java -cp out com.julian.demos.TilesDemo
# sample input:
# 3 16 23
# expected output:
# 48
