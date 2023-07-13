# npatlas_curator_guide

A website build using Jekyll and the [`just-the-docs`](https://pmarsceill.github.io/just-the-docs/) theme for deployment on GitHub pages.

This repo has been configured to use a VS Code [devcontainer](https://code.visualstudio.com/docs/remote/containers).

If you have [Docker](https://www.docker.com/) and the `Remote-Containers` extenstion installed, 
you can easily develop this static site locally before pushing changes to GitHub.

It takes just two steps:

1. Launch the devcontainer

Launch the Command Palette and select `Remote-Containers: Reopen in Container` command. This will reload your
VS Code window and build the necessary devcontainer where you can develop natively.

You can close this devcontainer with the `Remote-Containers: Folder Locally` command.

2. Start the Jekyll serve task

Launch the Command Palette and select `Tasks: Run Task` and then select `Serve`. This starts the Jekyll development server.

Alternatively, you can start a terminal and run the `bundle exec jekyll serve` command yourself. 
The container is pre-configured to expose the necessary ports for viewing the site in your browser with auto-reloading.s
