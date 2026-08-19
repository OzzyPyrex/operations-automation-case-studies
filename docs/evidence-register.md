# Evidence Register & Publication Decisions

This register prevents the portfolio from overstating what was recovered and prevents confidential files from being uploaded simply because a repository is private.

| Project | Evidence located | Source availability | Decision |
|---|---|---|---|
| Contact-centre reporting | PBIX reports, recurring spreadsheets, architecture image | Complete but confidential | Document methodology; rebuild synthetically for public use |
| NDLS contact reporting | PBIX report and source export | Complete but confidential | Fold into generic contact-centre case study |
| WAV grant analysis | PBIX and operational-impact report | Complete but confidential | Document methodology; fictional rebuild only |
| EV grant analysis | PBIX, report, dashboard export, and spreadsheet | Complete but confidential | Document methodology; fictional rebuild only |
| PSV17 OCR | Python source, GUI, workflow, and builds | Sanitised code available | Maintain separate code repository; exclude scans/logs/builds |
| Football sweepstake | Public deployment reviewed; original source not recovered | Deployment excluded because it contains identifiable staff and employer information | Publish only the clearly labelled reconstruction |
| Licence-renewal design | CV description | Original artifact unavailable | Generic design note only |
| Browser PDF editor | CV description | Original artifact unavailable | Generic security-focused concept note only |
| Job-search workflow | Tracker, workflow, and scheduled automation state | Working but contains personal/live data | Maintain sanitised sample repository only |
| Poster QA pipeline | Scripts, binaries/models, renders, and final QA outputs | Complete but high IP/privacy risk | Clean-room fictional rebuild required |
| ATS document generation | Python generators and personal outputs | Complete but personal | Template and fictional-profile rebuild required |

## Evidence labels

- **Verified:** Working source or completed output was directly inspected.
- **Described:** Supported by a CV/project description, but implementation source was not recovered.
- **Reconstruction:** A new portfolio-safe implementation based on the described behaviour, not the original internal source.

These labels should remain visible in every future public version.
