# sre-automation-toolkit-pilot
test repo for sre automation and config

# SRE Automation Toolkit

A collection of automation tools, infrastructure-as-code templates, monitoring configs, and CI/CD examples used by Site Reliability Engineers (SREs) to improve reliability, reduce toil, and standardize operations.

---

## 📦 Contents

### 1. Scripts (Bash)
Located in `/scripts`:
- `cleanup-old-containers.sh` – Cleans up unused Docker containers/images.
- `rotate-logs.sh` – Rotates & compresses logs.
- `check-disk-usage.sh` – Sends alerts when disk usage crosses threshold.

### 2. Terraform Templates
Located in `/terraform`:
- Sample AWS deployment with variables, outputs, tags, example VPC.

### 3. Ansible Playbook
Located in `/ansible`:
- OS hardening & dependency installation.

### 4. Monitoring
Located in `/monitoring`:
- Prometheus alert rules.
- A sample Grafana dashboard JSON.

### 5. CI/CD
Located in `/ci-cd`:
- GitHub Actions workflow example.
- Docker build/publish automation script.

---

## 🚀 How to Use

### Prerequisites
- Git installed
- GitHub account
- (Optional) AWS CLI, Terraform, Ansible installed

---

## 🔧 Running a Script Example

chmod +x scripts/check-disk-usage.sh
./scripts/check-disk-usage.sh


---

## 🌍 Deploying Terraform Example


cd terraform
terraform init
terraform plan
terraform apply


---

## ▶ Running Ansible Example


cd ansible
ansible-playbook -i inventory.ini playbook.yml


---

## 🧪 CI/CD (GitHub Actions)

Place `github-actions.yml` into:


.github/workflows/github-actions.yml


GitHub will automatically run your CI/CD pipeline.

---

## 🤝 Contribution

Feel free to modify anything or submit PRs.
