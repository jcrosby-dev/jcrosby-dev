```console
$ whoami
joshua-crosby


$ cat role.txt
Information Technology Specialist · Senior AI Engineer


$ cat about.txt
IT is my foundation: networks, systems, security and recovery. I build the software
that keeps infrastructure visible, patched and recoverable, and the data and ML
systems that run on it in fintech and healthcare. 10+ years in IT and engineering.
```


### 🏗️ The stack I think in


```text
┌──────────────────────────────────────────────────────────────┐
│  ML & AI          fraud scoring · readmission risk · RAG     │
├──────────────────────────────────────────────────────────────┤
│  Data             Kafka · Spark · PostgreSQL · data quality  │
├──────────────────────────────────────────────────────────────┤
│  Security & DR    patch compliance · backups · restore tests │
├──────────────────────────────────────────────────────────────┤
│  Infrastructure   inventory · networking · IPAM · Linux/Win  │  ← where I start
└──────────────────────────────────────────────────────────────┘
```


---


### 🖧 IT & infrastructure


#### Fleetkeeper · *IT asset inventory and patch compliance*
One view of every laptop, server and cloud instance, with machines behind their patch baseline flagged by owner and due date.
> Python · FastAPI · Celery · PostgreSQL · React


#### Subnet Atlas · *network discovery and IP address management*
Builds a live topology map over SNMP and LLDP and tracks every subnet, VLAN and address, flagging conflicts before they cause outages.
> SNMP · LLDP · NetworkX · Python · PostgreSQL


#### Backup Ledger · *backup and disaster-recovery verification*
Runs scheduled test restores and measures recovery point and recovery time per system, so backups are proven, not assumed.
> AWS S3 · Terraform · Grafana · Python · Docker


### 💳 Fintech & 🏥 healthcare


#### Settlement Stream · *real-time payment pipeline*
Moves payment events into a settlement ledger in real time with exactly-once posting and replay tooling.
> Kafka · Spark Streaming · PostgreSQL · Kubernetes


#### Chargeback Shield · *payments fraud prediction*
Scores card-not-present orders and routes them to approve, step-up or manual hold.
> Python · LightGBM · Kafka · Redis · FastAPI


#### Readmit Radar · *readmission risk at discharge*
Turns discharge data into a prioritized worklist for care coordinators, with per-patient explanations.
> Python · Spark · XGBoost · SHAP · MLflow


---


### ⚙️ How I work


1. **Know what you run.** You can't secure or recover what you don't know about.
2. **Prove recovery.** A backup only counts once it has been restored.
3. **Automate the routine.** People handle the exceptions.


### 🧰 Toolbox


- **Infrastructure:** Linux, Windows, SNMP, LLDP, DNS/DHCP, IPAM
- **Automation:** Python, FastAPI, Terraform, CI/CD
- **Data & ML:** Spark, Kafka, PostgreSQL, PyTorch, scikit-learn, MLflow
- **Cloud:** Docker, Kubernetes, AWS

