# Architect AWS Application Infrastructure

Infrastructure map:
• AWS Fargate service that does not serve traffic directly
• AWS ALB as the entry point to the Fargate Service
• AWS RDS Instance that is stored in a separate network from the Application and does not service traffic directly from the internet
