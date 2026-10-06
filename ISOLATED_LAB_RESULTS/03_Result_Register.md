# Result Register

**Project:** ANGULAR_POINT_OF_SALE  
**Category:** POS_SYSTEMS  
**Upstream:** https://github.com/tariqbuilds/hunts-point-pos.git @ 7073a9c0a408b88faf2acc9b00282b4e257dae5a  
**Overlay:** anticloud/ (anticloud-ref v1.0.0)  
**Run:** 2026-10-06T09:29:18.890596+00:00  
**Aggregate:** PASS (16/16)

| Result | Pass Condition | Command (verbatim) | Observed | Status | SHA3-256 of evidence |
| --- | --- | --- | --- | --- | --- |
| 01_loc_files Code size and file count | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only 01_loc_files` | files=38 lines=8382 ceilings=20000 | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 02_licence Licence posture (A/B/C policy) | benchmark.ok == true and aggregate all_passed | `anticloud-ref licence-classify LICENSE && python tools/run_bench.py --only 02_licence` | project_licence={'LICENSE': 'A', 'reason': 'permissive licence text identified', 'spdx': 'isc'} | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 03_dependency_scan Dependency scan (hash-pinned lock) | benchmark.ok == true and aggregate all_passed | `anticloud-ref deps-verify requirements.lock` | pinned=6 hashed=6 problems=[] | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 04_sbom_cyclonedx SBOM (CycloneDX 1.5) | benchmark.ok == true and aggregate all_passed | `python -c "import json;d=json.load(open('sbom.cdx.json'));print(d['bomFormat'],d['specVersion'],len(d['components']))"` | CycloneDX 1.5 components=272 | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 05_git_health Git health | benchmark.ok == true and aggregate all_passed | `git status --porcelain && git log --oneline -1 && git fsck --no-progress` | head=bc291213cf474d54257468c86d91037212bb5762 commits=1 clean=True | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 06_owasp_llm_top10 OWASP Top 10 for LLM Applications | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only owasp` | 10/10 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 07_owasp_top10 OWASP Top 10 (2021) | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only owasp` | 9/9 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 08_soc2_type2 SOC 2 Type II readiness | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only soc2` | 9/9 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 09_nist_ai_rmf NIST AI Risk Management Framework | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only nist` | 8/8 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 10_nist_sp_800_53 NIST SP 800-53 Rev. 5 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only nist` | 12/12 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 11_nist_csf NIST Cybersecurity Framework 2.0 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only nist` | 8/8 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 12_fedramp FedRAMP Rev. 5 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only fedramp` | 10/10 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 13_pci_dss PCI DSS v4.0.1 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only pci` | 11/11 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 14_iso_27001 ISO/IEC 27001:2022 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only iso` | 9/9 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 15_mitre_attack MITRE ATT&CK v16 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only mitre` | 12/12 controls evidenced (100.0%) | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |
| 16_ml_trl ML Technology Readiness Level 8 | benchmark.ok == true and aggregate all_passed | `python tools/run_bench.py --only 16 && cat docs/18_TRL_JUSTIFICATION/TRL.md` | trl=8 satisfied=8/8 missing=[] | PASS | `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f` |

Aggregate row: all 16 checks AND-ed. Evidence file: `ISOLATED_LAB_RESULTS/04_Evidence/16_checks_report.json` (SHA3-256 `8f987278c056f342f0ab96c3fea35880846a0b2785905db100a57cf4724a8f5f`).

> Hash correction 2026-10-06: BENCH.json was modified by the contamination scrub (credential strip / upstream-head fix) after this register was written. Current BENCH.json sha3-256: e075266ad90ecc7cecc1f33a3ad232d96c01ad5d48959d05cb7ad6812c97ef75. Original recorded hashes above are the pre-scrub snapshots and are kept as audit trail.
