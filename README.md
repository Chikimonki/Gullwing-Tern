# Gullwing-Tern — COBOL to Rust

The Tern dives deep into COBOL and emerges with Rust.
YouTube Video Evidence: https://youtu.be/mV92KhrJN6U

## What It Does

Translates COBOL source code to production-grade Rust — the language banks actually want for financial infrastructure.

| COBOL | Rust |
|-------|------|
| IDENTIFICATION DIVISION | struct definition |
| DATA DIVISION | struct fields |
| PROCEDURE DIVISION | impl block |
| IF/COMPUTE/MOVE | Control flow + expressions |
| DISPLAY | println! |

## Why Rust

- Memory-safe (no segfaults in settlement systems)
- Native performance (near-C)
- Auditable (strong type system)
- Production-ready (used by Microsoft, AWS, Google)

## Quick Start

```python
from src.cobol_rust import COBOLToRust
translator = COBOLToRust()
rust_code = translator.generate_rust_program(divisions)
```

## License

MIT
