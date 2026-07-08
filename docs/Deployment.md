# Deployment Guide

## Overview
This project is deployed and hosted on Vercel, which provides automatic builds and deployments directly from the Git repository.

## Initial Setup
1. Connect the GitHub repository to Vercel.
2. Configure the production branch (`main`) as the deployment source.
3. Add any required environment variables through the Vercel dashboard.

## Deployment Process
- Every push to the `main` branch automatically triggers a production deployment.
- Pull requests generate preview deployments for testing and review.

## Post-Deployment Checklist
- Verify that all pages load correctly.
- Test the contact form, newsletter signup, and EcoLoop beta waitlist.
- Confirm that the site displays properly on desktop and mobile devices.

## Rollback Procedure
If a critical issue is discovered, use the Vercel dashboard to instantly restore the previous successful deployment.

## Maintenance
All significant changes should be tested using Vercel preview deployments before being merged into the production branch.
