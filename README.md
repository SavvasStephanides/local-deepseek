# Install Deepseek Locally

1. Clone repository:

```sh
git clone https://github.com/SavvasStephanides/local-deepseek.git
```

2. Run the two apps from Docker Compose:

```sh
docker compose up -d
```

3. Install the Deepseek models: (This might take a few minutes)

```sh
docker compose exec ollama ollama pull deepseek-r1:7b
```

4. Run the website on http://localhost:3001

# Screenshots

Homepage:

![](https://github.com/user-attachments/assets/73226df6-3a3d-4ca3-bbdf-4edbb4c171b9)

Thinking box:

![](https://github.com/user-attachments/assets/1bdcdf28-158a-4ab6-b988-bc4b6689cf71)

Answer box:

![](https://github.com/user-attachments/assets/c7aa006e-9366-428c-a1d6-8b6432ba3557)

