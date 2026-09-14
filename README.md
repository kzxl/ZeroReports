# ZeroReports: Pure C# Document, Vector PDF & Thermal Label Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![.NET Multi-Targeting](https://img.shields.io/badge/.NET-8.0%20%7C%204.6.2%20%7C%20Standard%202.0-purple.svg)](https://dotnet.microsoft.com/)

**ZeroReports** is an enterprise-grade, zero-external-dependency document rendering and industrial thermal printer engine for .NET.

## Key Features

- **Pure C# Vector PDF 1.4**: In-memory PDF document generation (`PdfWriter`, `ReportDocument`) with native support for structured headers, tables, key-value pairs, and typography without native DLL dependencies.
- **Industrial Thermal Codecs**: High-performance command stream encoder (`ThermalEncoders`) for Zebra ZPL II (`^XA...^XZ`) and TSC TSPL thermal barcode/label printers.
- **Zero Allocations**: Optimized byte stream serialization directly to memory buffers or sockets.

## Multi-Targeting

- `.NET 8.0+`
- `.NET Framework 4.6.2+`
- `.NET Standard 2.0`

## License

MIT License. Copyright © 2026 Phong Võ (`kzxl`).
