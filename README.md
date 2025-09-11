# Big-RSS_337m Dataset

## Overview

**Big-RSS_337m** is a production-ready dataset containing 337 million web content records. This is a filtered subset of the full Big-RSS_1.1b dataset, designed for enterprise applications requiring structured web content intelligence.

## Dataset Specifications

- **Size**: 140GB
- **Format**: CSV
- **Records**: 337 million
- **Columns**: 4

## Data Schema

| Column | Type | Description |
|--------|------|-------------|
| `url` | String | Source URL |
| `content_mime_type` | String | Declared MIME type |
| `content_mime_detected` | String | Detected MIME type |
| `url_host_name` | String | Hostname |

## Access

**S3 Location**: `s3://authentik-rss-data/big-1.1b/7479cadc-dd1e-4b92-a373-22e399f24c63.csv`

**Billing**: Requester pays for S3 transfer and storage costs.

## Applications

- **Content Intelligence**: Web content classification and analysis
- **Domain Analysis**: Hostname and URL pattern analysis  
- **Data Validation**: MIME type verification and detection
- **Threat Intelligence**: URL and domain monitoring
- **Business Intelligence**: Web content tracking and analysis

## License

**Open Data Commons Attribution License (ODC-By) v1.0** - Free for commercial and non-commercial use.

## Citation

### BibTeX
```bibtex
@dataset{big_rss_337m_odin_glynn,
  author       = {Glynn-Martin, Odin},
  title        = {Big-RSS\_337m: Open-Web RSS Feed Dataset},
  year         = {2025},
  publisher    = {GitHub},
  url          = {https://huggingface.co/datasets/odinglynn/Big-RSS_337m}
}
```

### APA
Glynn-Martin, O. (2025). *Big-RSS_337m: Open-Web RSS Feed Dataset*. GitHub.

## Contact

**Odin Glynn-Martin**  
**Email**: odin@odinglynn.com

## Technical Details

- **Storage**: AWS S3 with requester-pays
- **Encoding**: UTF-8
- **Access Method**: Direct S3 download
