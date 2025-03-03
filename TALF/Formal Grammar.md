
A **formal grammar** is a mathematical system used to describe the syntax of a language. It consists of four components:

1. **Non-terminals (N)** – Symbols that can be replaced or expanded (e.g., S, A, B).
2. **Terminals (Σ)** – Symbols that appear in the final language (e.g., actual words or characters like `a`, `b`, `0`, `1`).
3. **Productions (P)** – Rules that define how non-terminals can be replaced (e.g., `S → aSb | ε`).
4. **Start symbol (S)** – A special non-terminal from which derivations begin.

A formal grammar generates a **formal language**, which can be classified in the **Chomsky hierarchy** based on the restrictions placed on production rules.

### Derivation process

Example:
- Non-terminals: `{S}`
- Terminals: `{0, 1}`
- Productions:
	- `S => 0S1`
	- `S => 01`
- Start symbol: `S`
- 
A derivation process to achieve 0⁵1⁵ would be:
- `S => 0S1 => 00S11 => 000S111 => 0000S1111 => 0000011111`