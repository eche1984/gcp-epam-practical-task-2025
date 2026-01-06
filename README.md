# epam-practical-task-2025 for GCP

The content of this repo was intended to complete the optional practical asignment in the course 'Cloud & Automation Tools LatAm November 2025', organized by EPAM.

## Asignment Statement

1) Create a Google Cloud Storage bucket and configure it to host a static website with public access. 
2) Create HTTP Load Balancer and configure it to use the bucket as the backend.
3) Create GitHub repo with a simple personal website. 
4) Deploy your site to Cloud Storage with GitHub Actions.


## Asignment Resolution

1) To complete this first task, a GCS bucket was created as 'gcp-epam-staticwebsite-bucket'.

2) To complete this second task, I created an Application Load Balancer (HTTP/HTTPS) named as 'epam-practical-task-lb'.

3) To complete this third task, I created this repo (gcp-epam-practical-task-2025).

4) Finally, to complete the last task, I created the deploy.yml file with a GitHub Action to upload the HTML files on every push.

To access to the site you can reach the following URL: http://34.128.177.200/
