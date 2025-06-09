# n8n on Render (Starter Plan)

This setup uses the official n8n Docker image, optimized for Render's Starter Plan.

## Instructions

1. Deploy this repo to Render as a Docker web service.
2. Add environment variables in Render as shown in `.env.example`.
3. Create a Persistent Disk:
   - Mount Path: `/home/node/.n8n`
   - Name: `n8n-data`
   - Size: 1GB or more
4. Point your custom domain to Render (e.g., `n8n.villalobosmario.com`)
5. Ensure SSL is enabled and use `https://` in `WEBHOOK_URL` and `N8N_HOST`.
