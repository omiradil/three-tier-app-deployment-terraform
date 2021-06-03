# Three tier app deployment with Terraform

```

From Team-1's, Team-2's and Team-3's modules build's fully functioning Three-Tier application:

* on top of the VPC(Team-1) ASG(Team-2) have WordPress image.
* RDS cluster available for ASG to store databases of WordPress.
* When building WordPress image, pass RDS clusters write endpoint in wp_config.php file


```