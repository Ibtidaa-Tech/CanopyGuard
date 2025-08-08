# CanopyGuard

**Tree Health & Urban Green-Cover Monitor**

## 🚀 Overview
CanopyGuard is an open-source platform that leverages drone imagery and vision-transformer AI to detect early signs of tree stress—such as leaf discoloration, pest infestation, and dead limbs—and displays a dynamic heatmap for urban green-cover health. Municipalities and NGOs can use this to allocate resources efficiently and improve city sustainability.

## 🔍 Features
- **Automated Flight Capture**: Ingests drone-collected RGB images.
- **Stress Detection**: Uses a PyTorch Vision Transformer model to flag unhealthy regions.
- **Geo-referenced Heatmap**: Overlays health metrics on interactive maps.
- **Dashboard**: Real-time tree-by-tree health visualization.
- **Alerts & Reports**: Exportable PDF and email/SMS notifications for at-risk areas.

## 🛠️ Tech Stack
- **Edge AI**: NVIDIA Jetson Nano / Xavier, PyTorch (ViT)
- **Backend**: FastAPI, PostgreSQL + PostGIS
- **Frontend**: Next.js, Tailwind CSS, Mapbox GL, Deck.gl
- **Infra & CI**: Docker, Kubernetes (GCP), GitHub Actions

## ⚙️ Quick Start
1. **Clone the repo**  
   ```bash
   git clone https://github.com/IbtidaaTech/CanopyGuard.git
   cd CanopyGuard
