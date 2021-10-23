# Alex Howard

[github.com/ahoward1024](https://www.github.com/ahoward1024/)

[ahoward1024@gmail.com](mailto:ahoward1024@gmail.com)

Phone \# available on request

## Working Experience

### Conga (2019 - Present)

#### Accomplishments

* Lead working sessions between engineering and security teams to work on organization wide security related tasks.
* Lead morning standup meetings for my team, making sure there were no blockers for team members and that throuput of
  work was consistent sprint to sprint.
* Part of a team that was asked to find solutions to reducing our AWS spend between 8% to 20% within a six month period.
  The goal was met with a reduction in spend of 23%.
* Migrated a product from being a non-containerized application running on ElasticBeanstalk to
  become a Dockerized application running on Kubernetes.
* Participated in a design review team that would look at and scrutinize the design of architectures, applications,
  and standards for the company.

#### Backend

* Wrote API services using .NET ASPNET Core framework utilizing the Mediator pattern to integrate into third-party
  APIs from Microsoft, Google, and Dropbox.
* Updated Java projects from being a Tomcat servlet container to SpringBoot to enable Dockerization to run on Kubernetes.

#### Infrastructure

* Wrote Terraform modules to make consistent deployments of Kubernetes clusters across multiple AWS accounts.
* Utilized Helmfile to deploy infrastructure applications into Kubernetes clusters

#### CI/CD

* Created GitHub Actions pipelines for  automatically packaging Docker images, running and deploying Terraform, running
  unit tests, and deploying infrastructure applications to Kubernetes clusters.
* Deployed company-internal Docker registry and Helm chart repository.
* Deployed and orchestrated Spinnaker to serve as a company wide continuous deployment tool. All
  applications deployed into Kubernetes clusters hooked into the company Docker registry and
  GitHub repos to deploy applications.
* Built a Selenium testing suite for doing integration tests in the browser.
  Integration test ran on TeamCity/GitHub Actions on deployment to staging environment.
* Deprecated TeamCity CI/CD pipelines and migrated them to GitHub Actions.

#### Frontend

* Wrote custom webpack and Babel configurations to minify a JavaScript bundle. This reduced the bundle size from over
  50MB to around 12MB.
* Created React components to replace an older user interface written in extJS.

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
