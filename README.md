# Kerala Assembly Election 2026 Results Dataset

This repository contains a candidate-level database of the 2026 Kerala Assembly election results.

The dataset includes constituency-wise candidate results along with party, alliance, gender and age information. Candidate age and gender data were scraped from the Election Commission of India’s candidate affidavit portal, while election-result fields were compiled from official election result data.

## Dataset

The main dataset contains candidate-level records for Kerala’s 2026 Assembly election.

### Key fields

- `constituency_no`: Assembly constituency number
- `constituency`: Assembly constituency name
- `constituency_type`: Constituency category
- `name`: Candidate name
- `party`: Political party
- `alliance`: Political alliance
- `gender`: Candidate gender, as recorded in affidavit data
- `age`: Candidate age, as recorded in affidavit data
- `position`: Candidate rank in the constituency by votes secured
- `votes`: Total votes secured
- `evm_votes`: EVM votes secured
- `postal_votes`: Postal votes secured
- `valid_votes`: Total valid votes in the constituency
- `vote_share_percentage`: Candidate vote share as a percentage of valid votes
- `margin`: Vote margin against the next candidate, where applicable
- `margin_percentage`: Margin as a percentage of valid votes
- `district_name`: District
- `sub_region`: Regional classification within Kerala
- `enop`: Effective number of parties
- `previous_winner`: Winning party in the previous Assembly election
- `previous_winner_alliance`: Alliance of the previous winner

## Sources

The data has been compiled from:

1. Election Commission of India election results portal: https://results.eci.gov.in/ResultAcGenMay2026/statewiseS111.htm
2. Election Commission of India Candidate Affidavit Management portal: https://affidavit.eci.gov.in/

The age and gender fields are based on candidate affidavit records available on the ECI affidavit portal.

## Important caveats

- The dataset is compiled from public official sources, but it is not an official ECI release.
- Candidate age and gender fields depend on the information available in affidavit records.
- The ECI affidavit portal describes its data as computer-generated, dynamically updated by returning officers, subject to change and tentative unless confirmed with the respective returning officer.
- Some cleaning and standardisation has been applied, especially for party names, alliance classification and regional labels.

## Suggested citation

> Krishnakumar, Sreedev. *Kerala Assembly Election 2026 Results Dataset*. Compiled from Election Commission of India results and candidate affidavit records. GitHub repository, 2026.

Please also acknowledge the Election Commission of India as the original source of the election and affidavit data.

## License

This dataset is released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
See the `LICENSE` file for details.

## Disclaimer

This repository is an independent compilation and cleaning of publicly available election data. It is not affiliated with, endorsed by, or maintained by the Election Commission of India.
