# Necessary Docker Commands after first run

Docker-ის პირველი გაშვების შემდეგ საჭირო ძირითადი ბრძანებები.

## სტრუქტურა

- `DockerEn.html` — ინგლისური ვერსია (card/grid დიზაინი)
- `DockerKa.html` — ქართული ვერსია (card/grid დიზაინი)
- `description.txt` — YouTube ვიდეოს აღწერა (KA + EN)

## ბრძანებები

### 1. არსებული დოკერიზაციის შემოწმება და ინფორმაცია (3 კამანდა)
```bash
docker --version
docker info
docker compose version
```

### 2. არსებული მდგომარეობის შემოწმება (4 კამანდა)
```bash
# Container-ის შემოწმება
docker ps

# Image-ების შემოწმება
docker images

# Volume-ების შემოწმება
docker volume ls

# Build-ის შემოწმება
build
```

### 3. სატესტო (5 კამანდა)
```bash
# Image-ის ჩამოტვირთვა
docker pull hello-world

# Container-ის გაშვება
docker run -d -p 80:80 hello-world

# Container-ის გაჩერება
docker stop my-web

# Container-ის წაშლა
docker rm my-web

# Image-ის წაშლა
docker rmi hello-world
```

### 4. მულტი კონტეინერების ორკესტრაცია/მართვა (6 კამანდა)
```bash
docker compose up -d
docker compose down
docker compose ps
docker compose logs
docker compose restart
docker compose build
```

## დიზაინი

იგივე card/grid სტილი როგორც Docker-30.08-ში:
- მუქი თემა (`#0a0f1e` background)
- Card გრადიენტით
- Hover ეფექტები (გამწვანება + scale)
- Tooltip აღწერით
- Click-ზე clipboard copy
