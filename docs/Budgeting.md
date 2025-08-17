# Operations & Cost Controls

## Cost Guardrails
- AWS Budget: $.01/month
- CloudWatch Billing Alarm: $.01 threshold
- Alerts go to: your-email@example.com

## Runbook
- If billing alert triggers:
  1. Log into AWS Console
  2. Check Amplify usage
  3. Pause/disable app builds if needed
  4. Confirm no rogue services are running
