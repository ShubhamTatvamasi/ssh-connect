# ssh-connect

Get docker permissions
```bash
sudo usermod -aG docker $USER
```
---

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

> just change the name and zone

elastic-stack  asia-southeast1-a

interiit-competition-mumbai  asia-south1-a

jenkins  asia-south1-a

nginx  asia-south1-a

openvpn-mumbai asia-south1-a

rabbitmq asia-south1-a

test-nginx asia-southeast1-a

vault  asia-south1-a
