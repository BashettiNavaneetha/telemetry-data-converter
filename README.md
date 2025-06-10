# Telemetry Data Converter

This project is a Python utility that converts telemetry JSON data from two different formats into a unified output format. It includes unit tests to validate the conversion logic.

## 🚀 Features

- Detects telemetry data type based on JSON structure
- Converts from Format 1 or Format 2
- Returns a standard output format
- Includes unit testing with `unittest`

## 📁 Files

| File Name        | Description                          |
|------------------|--------------------------------------|
| `main.py`        | Contains the core conversion logic and test cases |
| `data-1.json`    | Sample telemetry input in Format 1   |
| `data-2.json`    | Sample telemetry input in Format 2   |
| `data-result.json` | Expected output format             |
| `replit.nix`, `.replit` | Replit config files          |

## 🧪 How to Run Tests

```bash
python main.py
