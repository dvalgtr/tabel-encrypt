# Tabel Encryptor Tool

A comprehensive web-based encryption tool that supports multiple encryption methods including custom formulas.

## Features

- **Multiple Encryption Methods**:
  - Caesar Cipher
  - Custom Formula Cipher
  - Atbash Cipher
  - Reverse Text

- **Custom Formula Support**:
  - Input your own mathematical formulas using 'x' as character position
  - Real-time formula validation
  - Supports complex expressions like `(x + 7) % 26` or `(x * 3 + 5) % 26`

- **Substitution Table**:
  - Visual representation of character mappings
  - Supports all encryption methods
  - Easy-to-read A-Z conversion table

- **User-Friendly Interface**:
  - Dark theme with clean, modern design
  - Responsive layout for all devices
  - Real-time encryption/decryption

## Live Demo

Visit: https://dvalgtr.github.io/tabel-encrypt

## Usage

### Basic Encryption/Decryption

1. Enter text in the input field
2. Select encryption method
3. Configure parameters (shift value for Caesar, formula for custom)
4. Click "Encrypt" or "Decrypt"
5. View results in the output area

### Custom Formulas

- Use `x` to represent the character position (0-25, where A=0, B=1, ..., Z=25)
- Supported operators: `+`, `-`, `*`, `/`, `%`
- Use parentheses for complex expressions
- Examples:
  - `(x + 7) % 26` - Simple Caesar cipher with shift 7
  - `(x * 3 + 5) % 26` - Affine cipher
  - `25 - x` - Atbash equivalent

### Substitution Table

1. Select table method
2. Configure parameters
3. Click "Generate Table"
4. View how each letter transforms in the table

## Supported Methods

### Caesar Cipher
- Shifts each letter by a fixed number
- Customizable shift value (1-25)

### Custom Formula Cipher
- Apply any mathematical formula to character positions
- Formula validation included

### Atbash Cipher
- Reverses the alphabet (A→Z, B→Y, etc.)

### Reverse Text
- Reverses the entire text string

## Installation

1. Clone this repository:
```bash
git clone https://github.com/dvalgtr/tabel-encrypt.git
