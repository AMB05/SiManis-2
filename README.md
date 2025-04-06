# Simanis

Deteksi dan rekomendasi makanan bayi


## Installation

1. Build docker image

```bash
    docker build -t simanis-gizi .
```

2. Run docker image in detached mode and map to port 4001, 8000 is application port

```bash
    docker run -d -p 4001:8000 --name simanis-gizi simanis-gizi
```

3. Enjoy
    
