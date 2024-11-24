# LaTeX Docker

[![CI](https://github.com/DudeCalledBro/docker-latex/actions/workflows/ci.yml/badge.svg)](https://github.com/DudeCalledBro/docker-latex/actions/workflows/ci.yml)

This repository maintains the code for my LaTeX container image, which is designed to streamline the process of generating LaTeX documents. By utilizing this container image, users can easily integrate it into their CI/CD pipelines, enabling automated TeX build processes.

This setup not only enhances efficiency but also ensures consistency across different environments, making it easier to manage and compile LaTeX documents as part of a larger workflow. Whether for academic papers, reports, or presentations, this container image simplifies the complexities of document generation and allows for seamless collaboration among team members.

## Build

This image build is scheduled with GitHub Actions and will be pushed to DockerHub. The image will also be rebuilt, if the `main` branch is updated. If you need to build the image locally, ensure [Docker](https://docs.docker.com/engine/installation/) is installed and execute the following:

```bash
docker build -t docker-latex:latest .
```

## License

Copyright © 2024 Niclas Spreng

Licensed under the [MIT license](LICENSE).
