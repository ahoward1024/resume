# Alex Howard

[github.com/ahoward1024](https://www.github.com/ahoward1024/)

[ahoward1024@gmail.com](mailto:ahoward1024@gmail.com)

## Working Experience

 ### Fortra (AlertLogic) (2022 - Present)

* Worked on a Web Application Firewall product utilizing components written in Perl and Go, deployed
  primarily on EC2 instances using customized Oracle Linux distributions.
* Maintaned and upgraded EKS clusters from versions 1.22+ for an ETL application written in Go.
* Rewrote the Terraform/Shell script deployment process for upgrading the EKS clusters to working
  in parallel, bringing the upgrade process from around 6 hours to just over an hour.
* Transitioned Terraform templates to using Kustomize for deploying infrastructure applications
  in the EKS clusters.
* Wrote an IP address database in Go that found IP addresses from trusted, suspicious, and 
  untrusted sources around the internet. The IP databases were deployed to S3 buckets for other 
  teams and products to be able to consume. 
* Worked with a team member to create a machine learning process to add anomaly detection to a 
  product. We evaluating using the DBSCAN and isolation forest algorithms.
* Utilized the Go LEGO library to create a feature for provisioning of ACME certificates to 
  protect EC2 instances with SSL certificates.
* Built CI/CD pipelines for creating AMIs via Jenkins and Packer.

### Conga (2019 - 2021)

* Wrote company wide Terraform modules to make consistent deployments of Kubernetes clusters
  across multiple AWS accounts.
* Provisioned EKS clusters ensuring high levels of cluster scalability and hardening for security.
* Utilized Helmfile to deploy infrastructure applications into Kubernetes clusters to create
  standardized deployments for monitoring clusters using Kubernetes native tools and Datadog.
* Created GitHub Actions pipelines for  automatically packaging Docker images, running and
  deploying Terraform, running unit tests, and deploying infrastructure applications to
  Kubernetes clusters.
* Deployed company-internal Docker registry and Helm chart repository.
* Deployed and orchestrated Spinnaker to serve as a company wide continuous deployment tool. All
  applications deployed into Kubernetes clusters hooked into the company Docker registry and
  GitHub repos to deploy applications.
* Built a Selenium testing suite to perform functional tests in the browser to ensure 
  one-to-one compatibility of application functionality.
* Wrote integration tests to run on GitHub Actions.
* Wrote API services using .NET ASPNET Core framework utilizing the Mediator pattern to integrate 
  into third-party APIs from Microsoft, Google, and Dropbox.
* Updated Java applications from being Tomcat servlet containers to SpringBoot to enable
  Dockerization to run the applications in Kubernetes.
* Created React components to replace an older user interface written in extJS.

### Buzzwords:
AWS, API Gateway, RDS, Elasticache, EKS, SSM, IAM, KMS, EC2, DynamoDB, VPC, Kubernetes, Helm,
Kustomize, Go, React, NextJS, Datadog, Spinnaker, GitHub Actions, Git, Bash, Jenkins

## Personal Projects

### Winterleave (2018)
Cross platform video transcoder, successor to mouse (2016).
- Has the ability to do basic slicing of both video and audio streams.
- Decodes and plays audio and video files, with the ability to export to other formats, done in parallel.
- Written in C++ with dear imgui, SDL2, and FFMpeg, built using the Visual Studio  and Clang toolchains.

### Hex/Hex_static (2017)
Audio visualizer and player
- Draws and visualizes the wave form of WAV and Ogg Vorbis files in realtime while playing the audio.
- There are dynamically and statically linked versions to make distribution painless and convenient.
- Written in C++ with SDL2, built using the Visual Studio cl toolchain.

### mouse (2016)
x264/h264 video player.
- Simple WYSIWYG video player with the rare ability to accurately seek single frames both forwards and backwards.
- Written in C++ with SDL2 + FFmpeg, built using the Visual Studio cl toolchain.

### Avatar Generator (2017)
Contact profile picture creator.
- Generates a 2D PNG with a person's name, centered in a circle.
- The code for measuring glyph dimensions was written by hand.
- Uses the Google Material Design colors template as well as a full RGB color picker.
- Written in C++ with SDL2, OpenGL3, and dear imgui. Built using the Visual Studio cl-clang toolchain.
