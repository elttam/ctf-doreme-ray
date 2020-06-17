# Overview

**Title:** Doreme Ray  
**Category:** Web  
**Flag:** libctf{d0aad7a7-994a-4023-9c05-7f9529bbb64c}  
**Difficulty:** Trivial  

# Usage

The following will pull the latest 'elttam/ctf-doreme-ray' image from DockerHub, run a new container named 'libctfso-doreme-ray', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-doreme-ray \
  elttam/ctf-doreme-ray:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-doreme-ray' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-doreme-ray:latest
```

