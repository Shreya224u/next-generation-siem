# Next-Generation SIEM Framework Based on Graph-Augmented Intelligence

A Next-Generation Security Information and Event Management (SIEM) framework designed to centralize security logs, detect suspicious activities, and correlate related security events using rule-based detection, machine learning, and graph-based intelligence.

## Project Overview

Traditional SIEM systems often rely on predefined rules and generate large numbers of alerts that require manual investigation. This project aims to explore an integrated approach to security monitoring by combining conventional detection techniques with machine learning and graph-based event correlation.

The proposed framework is designed to process security logs from multiple sources, identify suspicious activities, assign risk scores, and support security incident investigation through centralized monitoring.

**Project Status:** In Progress

## Objectives

* Centralize security logs from different sources.
* Parse and normalize heterogeneous log data.
* Detect known threats using rule-based detection.
* Explore machine learning for attack classification and anomaly detection.
* Correlate related security events using graph-based intelligence.
* Assign risk scores to detected security events.
* Map relevant alerts to MITRE ATT&CK techniques.
* Provide a centralized security monitoring interface.

## Key Modules

1. **Log Ingestion:** Collection of security events from supported log sources.
2. **Log Preprocessing:** Parsing, cleaning, and normalization of heterogeneous logs.
3. **Threat Detection:** Rule-based detection and machine learning-based analysis.
4. **Event Correlation:** Grouping related security events using shared attributes.
5. **Risk Scoring:** Assessing the risk associated with detected activities.
6. **MITRE ATT&CK Mapping:** Associating relevant alerts with documented attack techniques.
7. **Centralized Monitoring:** Presenting security events and alerts through a monitoring interface.

## Technology Stack

* **Programming Language:** Python
* **Machine Learning:** Scikit-learn
* **Data Processing:** Pandas, NumPy
* **Visualization:** To be finalized according to the implemented dashboard
* **Dataset:** CICIDS2017 and suitable sample system logs
* **Threat Framework:** MITRE ATT&CK
* **Version Control:** Git and GitHub

## Proposed System Architecture

Log Sources → Log Ingestion → Log Preprocessing → Threat Detection → Event Correlation → Risk Scoring → Centralized Monitoring

Graph-based intelligence is intended to support the correlation of related events.

## Machine Learning Models

The proposed machine learning component includes:

* **Random Forest:** For attack classification.
* **Isolation Forest:** For anomaly detection.

The models and their performance will be documented after implementation and evaluation.

## Evaluation Metrics

The framework is intended to be evaluated using the following metrics, where applicable:

* Accuracy
* Precision
* Recall
* F1-score
* False Positive Rate
* Detection and response time

## Repository Structure

The repository will contain source code, documentation, sample logs, model files, tests, and screenshots as the project develops.

## Project Status

This project is currently under development. Features, implementation details, experimental results, and setup instructions will be updated as development progresses.

## Future Scope

* Integration of additional log sources.
* Advanced graph-based threat analysis.
* Improved anomaly detection.
* Real-time security monitoring.
* Automated incident investigation and response.

## Contributors

Shreya Mundhe

## License

This project is intended for academic and research purposes. See the LICENSE file for licensing terms.
