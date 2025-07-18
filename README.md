# Cyberdudebivash's Ransomware Protection and Recovery Application

## Description

This Flask web app provides ransomware protection and recovery with 2025 specs: real-time monitoring (watchdog), anomaly/ransomware detection, behavioral analysis (psutil), zero-trust isolation (firewall/process kill sim), immutable encrypted backups (Fernet/zip), vulnerability scanning (NVD), automated response, and recovery (restore).

**Note:** Educational sim. Backups local/encrypted. Run as admin for firewall. Access GUI at http://127.0.0.1:5000/.

## Requirements

- Python 3.x
- Packages: See `requirements.txt`

## Installation

1. Install: `pip install -r requirements.txt`
2. Run: `python app.py`

## Usage

### GUI Dashboard (Browser)
- Start/Stop Monitoring: File change detection.
- Run Scan: Behavioral/vuln checks.
- Backup/Restore: Encrypted backups.

### API Endpoints
- GET /api/scan: Run threat/vuln scan.
- POST /api/backup: {"folder": "path"} - Create backup.
- POST /api/restore: {"backup_file": "path"} - Restore.
- GET /api/start_monitor: Start monitoring.
- GET /api/stop_monitor: Stop monitoring.

## Latest Specs Included

- **Backups**: Immutable/encrypted/offline sim.<grok-card data-id="2ae175" data-type="citation_card"></grok-card><grok-card data-id="4fd778" data-type="citation_card"></grok-card><grok-card data-id="147383" data-type="citation_card"></grok-card><grok-card data-id="ebda49" data-type="citation_card"></grok-card><grok-card data-id="1c1fb8" data-type="citation_card"></grok-card>
- **Monitoring/Detection**: Real-time, AI/behavioral.<grok-card data-id="d91a57" data-type="citation_card"></grok-card><grok-card data-id="03c9e0" data-type="citation_card"></grok-card><grok-card data-id="fb10f7" data-type="citation_card"></grok-card><grok-card data-id="867a59" data-type="citation_card"></grok-card>
- **Access Controls/Zero-Trust**: Isolation/firewall.<grok-card data-id="f2b3bf" data-type="citation_card"></grok-card><grok-card data-id="b4cbc3" data-type="citation_card"></grok-card><grok-card data-id="6dcc00" data-type="citation_card"></grok-card><grok-card data-id="8df632" data-type="citation_card"></grok-card>
- **Updates/Vuln Scanning**: NVD integration.<grok-card data-id="430bc2" data-type="citation_card"></grok-card><grok-card data-id="8fb76f" data-type="citation_card"></grok-card><grok-card data-id="7e5c50" data-type="citation_card"></grok-card>
- **Training/Awareness**: Logs for review (expand for sim).<grok-card data-id="20f94e" data-type="citation_card"></grok-card><grok-card data-id="fb19f3" data-type="citation_card"></grok-card><grok-card data-id="fc9419" data-type="citation_card"></grok-card><grok-card data-id="fdb6ea" data-type="citation_card"></grok-card>
- **Endpoint/Firewall**: Included.<grok-card data-id="0d055f" data-type="citation_card"></grok-card><grok-card data-id="0527d6" data-type="citation_card"></grok-card>
- **Segmentation**: Firewall rules.<grok-card data-id="d99ceb" data-type="citation_card"></grok-card>
- **Encryption**: Backups/data.<grok-card data-id="5ce7de" data-type="citation_card"></grok-card>
- **Response/Recovery**: Automated, restore plan.<grok-card data-id="3c957a" data-type="citation_card"></grok-card><grok-card data-id="8c5ddf" data-type="citation_card"></grok-card><grok-card data-id="3cc62f" data-type="citation_card"></grok-card>
- **Supply Chain**: Vuln scans.<grok-card data-id="d58f10" data-type="citation_card"></grok-card><grok-card data-id="c7857e" data-type="citation_card"></grok-card>

## Limitations

- Simulations (e.g., no real ML; expand with TensorFlow).
- Local backups (add cloud for offline).
- Basic detection; integrate YARA/Signature-based for malware.

## License

MIT License.

##COPYRIGHT#CYBERDUDEBIVASH  2025