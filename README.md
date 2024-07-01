## 1. How to clone

--- 

**If you don't have any ssh keys:**

```bash
# Generate a new ssh key, replace your email with "your_email@example.com"
ssh-keygen -t ed25519 -C "your_email@example.com"

# Then simply run the command
git clone git@github.com:cenkerozkan/CoffeeGuide.git


```





---

## 2. How to run

**To run he project at once:**

```bash
# Create your .env file in the same directory with docker compose file.
# You may find the required credentials for .env file in .env.example file


# Create your .env
cp .env.example .env


# To run docker
docker compose up --build 
```
