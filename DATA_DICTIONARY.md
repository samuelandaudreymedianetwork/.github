# Samuel & Audrey Media Network Hugging Face Profile — Data Dictionary

## `samuelandaudreymedianetwork-huggingface-datasets.jsonl` and `.csv`

| Field | Description |
|---|---|
| `record_id` | Stable profile record identifier. |
| `record_type` | Record type. For dataset entries, this is `dataset_profile_entry`. |
| `dataset_name` | Human-readable dataset name. |
| `slug` | Hugging Face dataset slug. |
| `category` | Broad dataset category. |
| `summary` | Short description of the dataset. |
| `hugging_face_url` | Canonical Hugging Face dataset URL. |
| `doi_url` | DOI or archive URL where available. |
| `languages` | Main languages represented in the dataset. |
| `license` | Dataset license. |

## `samuelandaudreymedianetwork-sites.jsonl`

| Field | Description |
|---|---|
| `record_id` | Stable site record identifier. |
| `record_type` | Record type. For site entries, this is `network_site`. |
| `site` | Human-readable site name. |
| `focus` | Short description of the site’s purpose. |
| `url` | Canonical site URL. |

## Notes

This package is a profile/directory layer for the Hugging Face organization. It is not intended to duplicate the full datasets.

Use each dataset-specific repository for full data files, data dictionaries, schemas, limitations, and citation metadata.
