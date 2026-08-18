# KLH-CSE-2026-2027-Team03-MusicAnalyticsDataPlatform

## Project Title
**Music Analytics Data Platform**

---

## 📌 Project Overview & Metadata

* **Repository Name:** `KLH-CSE-2026-2027-Team03-MusicAnalyticsDataPlatform`
* **Academic Year:** 2026–2027
* **Branch:** Computer Science and Engineering (CSE)
* **Team ID:** Team 03
* **Institution:** Koneru Lakshmaiah Education Foundation (Deemed to be University, Estd. u/s 3 of UGC Act, 1956), Off-Campus: Bachupally-Gandimaisamma Road, Bowrampet, Hyderabad, Telangana - 500 043

---

## 👥 Team Details & Guidance

### Team Members
| S. No. | University ID | Student Name | Role / Focus Area |
|:---:|:---:|:---:|:---:|
| 1 | **2420030133** | **Y. Sai Charan Reddy** | Data Engineering & Pipeline Lead |
| 2 | **2420030135** | **Bhuvan Surisetti** | Platform Architecture & Analytics Lead |
| 3 | **2420030644** | **Eshwar .M** | Machine Learning & Dashboard Integration |

### Project Supervisor / Guide
* **Supervisor Name:** Dr.N.Shirisha
* **Designation:** Associate Professor
* **Department:** Department of Computer Science and Engineering
* **Institution:** Koneru Lakshmaiah Education Foundation (KL University), Hyderabad Off-Campus

---

## 📝 Abstract

Music streaming platforms and independent artists often encounter challenges in managing large-scale telemetry data, tracking listener engagement, and identifying emerging industry trends, which can lead to missed promotional opportunities, inaccurate content targeting, and delayed strategic decisions. 

This project proposes a **comprehensive music platform analytics dashboard with integrated AI insights and predictive modeling features** to address these issues. The application enables stakeholders to seamlessly monitor overview metrics, view real-time artist and song performance, and analyze listener behavior, while also offering advanced features such as **dynamic skip-rate tracking, completion-rate evaluations, genre popularity trend mapping, automated natural language business highlights, and machine learning-driven recommendations for upcoming tracks and artist growth**. 

By combining descriptive analytics, real-time telemetry processing, and predictive intelligence into a single platform, the system aims to enhance data accessibility, improve content discovery efficiency, reduce listener churn, and ensure timely strategic decision-making in the competitive streaming industry.

---

## 🚀 Introduction

Efficient data-driven decision-making in the music streaming ecosystem depends on reliable telemetry analysis, real-time listener engagement tracking, and timely trend identification. However, many music platforms and independent artists still rely on manual or fragmented data tools, causing delays, miscommunication, and missed promotional opportunities. 

In competitive streaming environments, stakeholders often face difficulties interpreting large-scale streaming logs or forecasting audience growth, which can lead to inaccurate content targeting and critical strategic risks. To overcome these challenges, this project introduces a **comprehensive music platform analytics dashboard with integrated AI insights and predictive modeling features**. 

The system provides stakeholders with an easy-to-use platform for monitoring macro-level overview metrics, checking artist and song performance, and analyzing listener behavior, while also integrating advanced features such as:
* **Dynamic Skip-Rate Tracking**: Monitoring user drop-off points within track audio timelines.
* **Completion-Rate Evaluations**: Measuring full stream fidelity and engagement metrics.
* **Genre Popularity Trend Mapping**: Visualizing shift in listener tastes across geographic & demographic clusters.
* **Automated Natural Language Business Highlights**: Summarizing key platform metrics into actionable executive briefs.
* **Machine Learning-Driven Recommendations**: Forecasting upcoming track trajectories and suggesting targeted artist growth strategies.

This solution aims to improve data accessibility, reduce listener churn, and ensure faster strategic decision-making when needed.

---

## 📂 Repository Structure

This repository strictly complies with the mandatory directory layout:

```text
KLH-CSE-2026-2027-Team03-MusicAnalyticsDataPlatform/
├── README.md              # Project documentation, abstract, setup & compliance details
├── data/                  # Raw/Processed dataset storage or data source schema references
│   └── README.md          # Data source descriptions & schema definitions
├── docs/                  # Architectural diagrams, design documentation & specification files
├── reports/               # Phase review presentations, progress reports, & deliverables
│   └── Project Review Meeting FDE (2).pptx  # Review-1 Presentation
├── results/               # Model evaluation outputs, analytics benchmarks, & visual charts
└── src/                   # Core application source code, data pipelines, & ML models
    ├── analytics/         # Telemetry aggregation & descriptive analytics scripts
    ├── dashboard/         # Interactive UI components & visualization modules
    └── models/            # Machine learning predictive models & recommendation engines
```

---

## ⚙️ Setup and Execution Instructions

### Prerequisites
* **Python**: 3.9 or higher
* **Git**: Installed and configured with your individual GitHub account credentials
* **Virtual Environment Tool**: `venv` or `conda`

### Step 1: Clone the Repository
```bash
git clone https://github.com/bhuvan-surisetti/KLH-CSE-2026-2027-Team03-MusicAnalyticsDataPlatform.git
cd KLH-CSE-2026-2027-Team03-MusicAnalyticsDataPlatform
```

### Step 2: Set Up Virtual Environment
```bash
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Dependencies
```bash
pip install --upgrade pip
# Install core requirements once requirements.txt is populated in /src
if [ -f src/requirements.txt ]; then pip install -r src/requirements.txt; fi
```

### Step 4: Data Reference Configuration
Raw telemetry data logs should be placed in the `/data` directory or configured via environment variables for remote storage (e.g., S3 / GCS bucket references). Refer to [`data/README.md`](data/README.md) for data format specs.

### Step 5: Run the Analytics Dashboard
```bash
# Execute application runner from /src
python src/main.py
```

---

## 📊 Current Phase Status

| Phase / Milestone | Status | Deliverable Tag | Target Date |
|:---|:---:|:---:|:---:|
| **Phase 1: Project Initialization & Review-1** | ✅ **Completed** | `review-1` | August 2026 |
| **Phase 2: Data Pipeline & Baseline Analytics** | 🔄 In Progress | `review-2` | Upcoming |
| **Phase 3: AI Predictive Engine & Recommendations** | ⏳ Scheduled | `review-3` | Upcoming |
| **Phase 4: Final Platform Deployment & Evaluation** | ⏳ Scheduled | `final` | Upcoming |

---

## 📜 Repository Rules & Compliance Assurance

This repository strictly adheres to the governing rules specified for academic project tracking:

1. **Repository Naming Standard**: Named as `KLH-CSE-2026-2027-Team03-MusicAnalyticsDataPlatform` following the `KLH-<Branch>-<AcademicYear>-<TeamID>-<ShortProjectName>` convention.
2. **Single Repository Rule**: Retained as the single official repository for Team 03 for the complete duration of the project.
3. **Mandatory Folder Structure**: Maintained `/src`, `/docs`, `/data`, `/results`, `/reports`, and top-level `README.md`.
4. **Individual Contribution Accountability**: Every team member commits using their individual GitHub account (`Y. Sai Charan Reddy`, `Bhuvan Surisetti`, `Eshwar .M`) to ensure contribution transparency. Bulk single-user uploads are prohibited.
5. **Progressive Commit Cadence**: Minimum of one meaningful commit per week per team throughout each phase.
6. **Phase Tagging**: Deliverables are tagged at each review checkpoint (`review-1`, `review-2`, `final`).
7. **Access Control**: Read/Write access granted to the Project Supervisor (Dr. Shirisha) and Course Coordinator until final project evaluation.
8. **Security & Confidentiality**: Credentials, API keys, licensed datasets, and institutional sensitive data are strictly excluded and managed via `.gitignore` / environment variables.
9. **URL Immutability**: The repository URL will not be renamed or transferred without prior written approval from the Course Coordinator.
