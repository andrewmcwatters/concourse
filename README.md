# concourse
hello-world.yml from "1.1.2 Hello World Pipeline" of Concourse CI Docs

## Run the pipeline
```sh
$ fly -t tutorial set-pipeline -p hello-world -c hello-world.yml
# pipelines are paused when first created
$ fly -t tutorial unpause-pipeline -p hello-world
# trigger the job and watch it run to completion
$ fly -t tutorial trigger-job --job hello-world/hello-world-job --watch
```

## License
Copyright © 2021 concourse. All rights reserved.
