# ssh-connect

Get docker permissions
```bash
sudo usermod -aG docker $USER
```
---

alias for quick access
```bash
alias ssh-qa='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a qa-mumbai'
alias ssh-dev='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a dev-competition-mumbai'
alias ssh-test='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a test-competition-mumbai'
alias ssh-stag='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a staging-competition-mumbai'
alias ssh-prod='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a production-competition-mumbai'
alias ssh-nginx='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a nginx'
alias ssh-jenkins='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a jenkins'
alias ssh-vault='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a vault'
alias ssh-test-nginx='gcloud compute ssh --project bitgrit-competition-platform --zone asia-southeast1-a test-nginx'
alias ssh-openvpn='gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a openvpn-mumbai'
```

qa-mumbai
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a qa-mumbai
```

test-competition-mumbai
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a test-competition-mumbai
```

dev-competition-mumbai
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a dev-competition-mumbai
```

staging-competition-mumbai
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a staging-competition-mumbai
```

production-competition-mumbai
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a production-competition-mumbai
```
---

interiit-competition-mumbai
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a interiit-competition-mumbai
```
---

jenkins
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a jenkins
```

nginx
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a nginx
```

openvpn-mumbai
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a openvpn-mumbai
```

vault
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-south1-a vault
```

test-nginx
```bash
gcloud compute ssh --project bitgrit-competition-platform --zone asia-southeast1-a test-nginx
```

> just change the name and zone

elastic-stack  asia-southeast1-a

rabbitmq asia-south1-a
