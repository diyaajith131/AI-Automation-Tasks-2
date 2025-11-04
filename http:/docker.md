 `markdown
    # Task 2: n8n with Docker

    This task involved setting up and running the n8n workflow automation tool inside a Docker container.

    ## Installation Steps

    1.  **Signed up** for a free account at `https://n8n.io`.
    2.  **Received** the license/activation key via email.
    3.  **Pulled** the n8n Docker image.
    4.  **Ran** the container with basic authentication enabled.
    5.  **Accessed** n8n at `http://localhost:5678`.
    6.  **Logged in** and activated the instance using the license key.

    ## Docker Commands

    **1. Pull Image:**
    bash
    docker pull n8nio/n8n
    `
 **2. Run Container:**

    bash
    docker run -it --rm \
      -p 5678:5678 \
      -e N8N_BASIC_AUTH_ACTIVE=true \
      -e N8N_BASIC_AUTH_USER=admin \
      -e N8N_BASIC_AUTH_PASSWORD=my-secure-password-was-here \
      n8nio/n8n
    

    ## Dashboard Screenshot

    Here is the activated n8n dashboard running on `localhost:5678`.

    
