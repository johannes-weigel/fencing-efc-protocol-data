# EFC Protocol Data (Unofficial)

This repository provides a structured, **unofficial** collection of data related to countries used for protocol purposes by the **European Fencing Confederation (EFC)**. It includes standardized country abbreviations, sorting orders, flags, anthems, and additional metadata intended to support consistent and respectful presentation during fencing events.

## Disclaimer

> This is **not an official repository** of the European Fencing Confederation.  
> It is a personal initiative to support event organizers and developers working with protocol-relevant data.  
> For official information, please refer to the EFC's, FIE's or IOC's official website.

## Purpose

To provide a reusable and version-controlled source of country-related data to help ensure consistency during:

- medal ceremonies,
- opening/closing ceremonies,
- presentation of participants,
- and other protocol-related activities.

## Contents

- **Country list**: Official country names (English), IOC codes
- **Sorting order**: Predefined order for protocol events (EFC and FIE)
- **Flags**: Digital country flags in standardized SVG/PNG format
- **Anthems**: National anthems in MP3 (if available)
- **Metadata**: Additional fields like IOC codes, continent classification, language codes

## Structure

```text
.
├── data/
│   ├── countries.json
│   ├── flags/
│   │   ├── [COUNTRY_CODE].png
│   │   └── [COUNTRY_CODE].svg
│   └── anthems/
│       └── [COUNTRY_CODE].mp3
└── README.md
```

## File Formats

- `JSON` for structured data (e.g., countries and metadata)
- `SVG` for vector-based flags
- `MP3` for anthem audio

## Usage

These resources can be used by applications or event software to ensure standardized protocol behavior, such as:

- Displaying country flags during events
- Playing national anthems during medal ceremonies
- Generating official participant listings
- Sorting nations in a fixed order for ceremonies

## Contributing

Contributions are welcome. Please make sure that:

- Data entries are accurate and up to date
- Media files follow the naming and formatting conventions
- All media complies with licensing or public domain requirements

## License

This project is published under the **MIT License** unless stated otherwise.  
Note: Licensing for media content (flags, anthems) may vary and should be reviewed before use in public or commercial settings.

---

This project is maintained independently and is not affiliated with or endorsed by the European Fencing Confederation.
