# keccak
Pure PHP implementation of Keccak hash algorithm with 224- or 256-bits digest.

Based on Bruno Bierbaumer's script, with change of padding rule and cleanup of patches for multibyte operations

## Usage

```
<?php

use Keccak\Keccak256;

// returns: c5d2460186f7233c927e7db2dcc703c0e500b653ca82273b7bfad8045d85a470
Keccak256::hash('', 256);

// for raw (binary) output
Keccak256::hash('', 256, true)

?>
