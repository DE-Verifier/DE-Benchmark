# DE-Benchmark Materials

## Overview
| Split | Count |
| --- | --- |
| Total traces | 208 |
| Malicious traces | 15 |
| Benign traces | 193 |
| Benign — common operations | 168 |
| Benign — adversarial admin | 25 |

## Malicious Trace Taxonomy
| Provider | Trace IDs | Attack Class | Flaw ID |
| --- | --- | --- | --- |
| GCP | `gcp_attack_1`, `gcp_attack_2`, `gcp_attack_3` | Confused Deputy | Flaw 1 |
| Azure | `azure_attack_3`, `azure_attack_6` | Confused Deputy | Flaw 2 |
| AWS | `aws_attack_3`, `aws_attack_4` | Agent Takeover | Flaw 3 |
| Azure | `azure_attack_4`, `azure_attack_5` | Agent Takeover | Flaw 3 |
| Azure | `azure_attack_1`, `azure_attack_2` | Agent Takeover | Flaw 4 |
| AWS | `aws_attack_1`, `aws_attack_2`, `aws_attack_5`, `aws_attack_6` | Agent Takeover | Flaw 5 |

## Adversarial Benign Illustration
| Provider | Example traces |
| --- | --- |
| AWS | `benign/aws/aws_2.jsonl`, `aws_12.jsonl`, `aws_16.jsonl`, `aws_32.jsonl`, `aws_43.jsonl`, `aws_45.jsonl`, `aws_56.jsonl`, `aws_57.jsonl`, `aws_59.jsonl`, `aws_62.jsonl`, `aws_89.jsonl`, `aws_91.jsonl`, `aws_94.jsonl`, `aws_96.jsonl`, `aws_97.jsonl`, `aws_99.jsonl` |
| Azure | `benign/azure/azure_7.jsonl`, `azure_10.jsonl`, `azure_12.jsonl`, `azure_14.jsonl`, `azure_16.jsonl`, `azure_19.jsonl` |
| GCP | `benign/gcp/gcp_15.jsonl`, `gcp_22.jsonl`, `gcp_34.jsonl` |

