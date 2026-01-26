## 👋 Welcome to scrutiny 🚀

Hard drive monitoring with S.M.A.R.T metrics

## 📋 Description

Hard drive monitoring with S.M.A.R.T metrics

## 🚀 Services

- **app**: ghcr.io/analogj/scrutiny:master-omnibus

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/scrutiny/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/scrutiny" ~/.local/srv/docker/scrutiny
cd ~/.local/srv/docker/scrutiny
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install scrutiny
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:8080

## 📂 Volumes

- `./rootfs/data/scrutiny` - Data storage

## 🔍 Logging

```shell
docker compose logs -f app
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
